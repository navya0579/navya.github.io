1<!DOCTYPE html>
2<html lang="en">
3<head>
4    <meta charset="UTF-8">
5    <meta name="viewport" content="width=device-width, initial-scale=1.0">
6    <title>Simple Shopping Website</title>
7    <link rel="stylesheet" href="styles.css"> <!-- Link to an external CSS file -->
8    <style>
9        body {
10            font-family: Arial, sans-serif;
11            margin: 0;
12            padding: 0;
13            background-color: #f4f4f4;
14        }
15        header {
16            background: #35424a;
17            color: #ffffff;
18            padding: 10px 0;
19            text-align: center;
20        }
21        nav {
22            margin: 20px 0;
23        }
24        nav a {
25            margin: 0 15px;
26            text-decoration: none;
27            color: #35424a;
28        }
29        .container {
30            display: flex;
31            flex-wrap: wrap;
32            justify-content: center;
33            padding: 20px;
34        }
35        .product {
36            background: #ffffff;
37            border: 1px solid #ddd;
38            border-radius: 5px;
39            margin: 10px;
40            padding: 15px;
41            width: 200px;
42            text-align: center;
43        }
44        .product img {
45            max-width: 100%;
46            height: auto;
47        }
48        footer {
49            text-align: center;
50            padding: 10px 0;
51            background: #35424a;
52            color: #ffffff;
53            position: relative;
54            bottom: 0;
55            width: 100%;
56        }
57    </style>
58</head>
59<body>
60
61<header>
62    <h1>Simple Shopping Website</h1>
63</header>
64
65<nav>
66    <a href="#home">Home</a>
67    <a href="#products">Products</a>
68    <a href="#contact">Contact</a>
69</nav>
70
71<section id="products" class="container">
72    <h2>Products</h2>
73    <div class="product">
74        <img src="https://via.placeholder.com/150" alt="Product 1">
75        <h3>Product 1</h3>
76        <p>$10.00</p>
77        <button>Add to Cart</button>
78    </div>
79    <div class="product">
80        <img src="https://via.placeholder.com/150" alt="Product 2">
81        <h3>Product 2</h3>
82        <p>$15.00</p>
83        <button>Add to Cart</button>
84    </div>
85    <div class="product">
86        <img src="https://via.placeholder.com/150" alt="Product 3">
87        <h3>Product 3</h3>
88        <p>$20.00</p>
89        <button>Add to Cart</button>
90    </div>
91    <div class="product">
92        <img src="https://via.placeholder.com/150" alt="Product 4">
93        <h3>Product 4</h3>
94        <p>$25.00</p>
95        <button>Add to Cart</button>
96    </div>
97</section>
98
99<footer>
100    <p>&copy; 2023 Simple Shopping Website</p>
101</footer>
102
103</body>
104</html>
