# ONLINE-MARKETING-PLACES

This is an online marketplace application that allows users to add products to their cart, display cart items, and perform various operations on modules and products. The application is implemented using Python and utilizes a hybrid data structure composed of hash maps, a binary search tree, and a graph to efficiently manage and process the data.

Features Module Management: Users can add, update, and delete modules, which represent different brands of products. Modules are stored in a hash map for fast access and modification.

Cart Management: Users can add products to their cart and remove products from the cart. The cart functionality is implemented using a separate hash map for efficient storage and retrieval.

Product Search: Users can search for products by name or within a specific price range. The search functionality is implemented using a binary search tree, allowing for quick retrieval of products based on their names or prices.

Graph-based Operations: The application constructs a graph based on the data from a CSV file. The graph is used to perform operations such as finding minimum spanning trees, enabling efficient computations related to product prices and their relationships.

Performance and Efficiency The hybrid data structure used in the application combines the strengths of hash maps, binary search trees, and graphs to achieve efficient operations and data management. Here are some key performance aspects:

Time Complexity: The application optimizes time complexity through hash map operations, which offer constant time complexity (O(1)) for adding, updating, and deleting modules and products. The binary search tree provides logarithmic time complexity (O(log n)) for searching products by name or within a price range. Graph-related operations, such as constructing the graph and finding minimum spanning trees, have a complexity of O(V + E), where V represents the number of vertices and E represents the number of edges.

Space Complexity: The space complexity of the hybrid data structure depends on the number of modules, products, vertices, and edges. It ranges from O(M + P + V + E), where M is the number of modules, P is the number of products, V is the number of vertices, and E is the number of edges.

Usage upload the .ipynb in google collab and upload the word document in your google drive link those two files and run with the inputs as you want

Credits The code and implementation of the online marketplace application were developed by thilaknath reddy - cb.en.u4cse21010 , b sri ganesh - cb.en.u4cse21011, krishna aditya - cb.en.u4cse21051, vignesh - cb.en.u4cse2101068

