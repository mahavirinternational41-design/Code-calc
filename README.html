<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Price Calculator with Secret Code</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        /* Login Screen */
        .login-screen {
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 50px rgba(0, 0, 0, 0.3);
            padding: 40px;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 500px;
        }

        .login-screen h1 {
            color: #333;
            margin-bottom: 30px;
            font-size: 2rem;
        }

        .code-display {
            background: #f0f0f0;
            border: 2px solid #667eea;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            font-size: 1.5rem;
            font-weight: bold;
            color: #667eea;
            letter-spacing: 3px;
            word-break: break-all;
        }

        .code-buttons {
            display: flex;
            gap: 10px;
            justify-content: center;
            margin: 20px 0;
        }

        .btn {
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            transition: all 0.2s;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .btn-primary {
            background: #667eea;
            color: white;
        }

        .btn-primary:hover {
            background: #5568d3;
        }

        .btn-secondary {
            background: #48bb78;
            color: white;
        }

        .btn-secondary:hover {
            background: #38a169;
        }

        .btn-danger {
            background: #f56565;
            color: white;
        }

        .btn-danger:hover {
            background: #e53e3e;
        }

        .input-group {
            margin: 20px 0;
            display: flex;
            gap: 10px;
        }

        .input-group input {
            flex: 1;
            padding: 12px;
            border: 2px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.2s;
        }

        .input-group input:focus {
            outline: none;
            border-color: #667eea;
        }

        .message {
            margin: 15px 0;
            padding: 12px;
            border-radius: 5px;
            font-weight: bold;
        }

        .message.error {
            background: #fed7d7;
            color: #c53030;
        }

        .message.success {
            background: #c6f6d5;
            color: #22543d;
        }

        /* Main App */
        .app-screen {
            display: none;
        }

        .header {
            background: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .header h1 {
            color: #333;
            font-size: 1.8rem;
        }

        .user-info {
            text-align: right;
        }

        .user-info p {
            color: #666;
            margin: 5px 0;
        }

        .logout-btn {
            background: #f56565;
            color: white;
            padding: 10px 20px;
            margin-top: 10px;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .card h2 {
            color: #333;
            margin-bottom: 20px;
            font-size: 1.5rem;
            border-bottom: 2px solid #667eea;
            padding-bottom: 10px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            color: #333;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 2px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.2s;
        }

        .form-group input:focus {
            outline: none;
            border-color: #667eea;
        }

        .product-list {
            max-height: 500px;
            overflow-y: auto;
        }

        .product-item {
            background: #f9f9f9;
            border-left: 4px solid #667eea;
            padding: 15px;
            margin-bottom: 12px;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .product-info h3 {
            color: #333;
            margin-bottom: 5px;
        }

        .product-info p {
            color: #666;
            font-size: 0.9rem;
        }

        .product-price {
            font-size: 1.5rem;
            font-weight: bold;
            color: #48bb78;
        }

        .product-actions {
            display: flex;
            gap: 8px;
        }

        .btn-small {
            padding: 8px 12px;
            font-size: 0.85rem;
        }

        .delete-btn {
            background: #f56565;
            color: white;
        }

        .delete-btn:hover {
            background: #e53e3e;
        }

        .stats {
            background: #f0f0f0;
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
        }

        .stat-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }

        .stat-item:last-child {
            border-bottom: none;
        }

        .stat-label {
            color: #666;
        }

        .stat-value {
            font-weight: bold;
            color: #333;
            font-size: 1.1rem;
        }

        @media (max-width: 768px) {
            .content {
                grid-template-columns: 1fr;
            }

            .header {
                flex-direction: column;
                text-align: center;
            }

            .user-info {
                text-align: center;
                margin-top: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Login Screen -->
        <div class="login-screen" id="loginScreen">
            <h1>🔐 Product Price Calculator</h1>
            <p style="color: #666; font-size: 1.1rem; margin-bottom: 30px;">Secure Access with Auto-Generated Code</p>
            
            <div>
                <p style="color: #333; margin-bottom: 10px; font-weight: bold;">Your Secret Access Code:</p>
                <div class="code-display" id="secretCode">GENERATING...</div>
                <p style="color: #999; font-size: 0.9rem; margin-top: 10px;">Share this code to grant access</p>
            </div>

            <div class="code-buttons">
                <button class="btn btn-secondary" onclick="generateNewCode()">Generate New Code</button>
                <button class="btn btn-secondary" onclick="copyToClipboard()">Copy Code</button>
            </div>

            <p style="color: #666; margin: 30px 0 15px 0; font-weight: bold;">Or Enter Secret Code to Login:</p>
            
            <div class="input-group">
                <input type="password" id="codeInput" placeholder="Enter secret code..." onkeypress="handleEnter(event)">
                <button class="btn btn-primary" onclick="verifyCode()">Login</button>
            </div>

            <div id="loginMessage"></div>
        </div>

        <!-- Main App -->
        <div class="app-screen" id="appScreen">
            <div class="header">
                <h1>💰 Product Price Manager</h1>
                <div class="user-info">
                    <p id="userCode"></p>
                    <button class="btn logout-btn" onclick="logout()">Logout</button>
                </div>
            </div>

            <div class="content">
                <!-- Add Product Card -->
                <div class="card">
                    <h2>➕ Add New Product</h2>
                    
                    <div class="form-group">
                        <label>Product Name</label>
                        <input type="text" id="productName" placeholder="e.g., iPhone 14 Pro">
                    </div>

                    <div class="form-group">
                        <label>Product Price ($)</label>
                        <input type="number" id="productPrice" placeholder="0.00" step="0.01" min="0">
                    </div>

                    <div class="form-group">
                        <label>Category</label>
                        <input type="text" id="productCategory" placeholder="e.g., Electronics">
                    </div>

                    <div class="form-group">
                        <label>Description (Optional)</label>
                        <input type="text" id="productDescription" placeholder="Brief description...">
                    </div>

                    <button class="btn btn-primary" onclick="addProduct()" style="width: 100%;">Add Product</button>

                    <div id="addMessage" style="margin-top: 15px;"></div>

                    <div class="stats">
                        <div class="stat-item">
                            <span class="stat-label">Total Products</span>
                            <span class="stat-value" id="totalProducts">0</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-label">Total Value</span>
                            <span class="stat-value" id="totalValue">$0.00</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-label">Average Price</span>
                            <span class="stat-value" id="averagePrice">$0.00</span>
                        </div>
                    </div>
                </div>

                <!-- Products List Card -->
                <div class="card">
                    <h2>📦 Products List</h2>
                    <div class="product-list" id="productsList">
                        <p style="color: #999; text-align: center; padding: 40px 0;">No products added yet</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Initialize
        let secretCode = '';
        let isLoggedIn = false;
        let products = [];

        // Initialize on page load
        window.onload = function() {
            generateNewCode();
            loadFromLocalStorage();
        };

        // Generate random secret code
        function generateNewCode() {
            const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789';
            secretCode = '';
            for (let i = 0; i < 8; i++) {
                secretCode += chars.charAt(Math.floor(Math.random() * chars.length));
            }
            document.getElementById('secretCode').textContent = secretCode;
            localStorage.setItem('appSecretCode', secretCode);
        }

        // Copy code to clipboard
        function copyToClipboard() {
            navigator.clipboard.writeText(secretCode).then(() => {
                showLoginMessage('Code copied to clipboard!', 'success');
            });
        }

        // Handle Enter key
        function handleEnter(event) {
            if (event.key === 'Enter') {
                verifyCode();
            }
        }

        // Verify secret code
        function verifyCode() {
            const inputCode = document.getElementById('codeInput').value.trim().toUpperCase();
            
            if (inputCode === '' || inputCode === 'GENERATING...') {
                showLoginMessage('Please enter a code', 'error');
                return;
            }

            if (inputCode === secretCode) {
                isLoggedIn = true;
                document.getElementById('loginScreen').style.display = 'none';
                document.getElementById('appScreen').style.display = 'block';
                document.getElementById('userCode').textContent = `Logged in with code: ${secretCode}`;
                document.getElementById('codeInput').value = '';
            } else {
                showLoginMessage('Invalid secret code!', 'error');
                document.getElementById('codeInput').value = '';
            }
        }

        // Show login message
        function showLoginMessage(text, type) {
            const messageDiv = document.getElementById('loginMessage');
            messageDiv.textContent = text;
            messageDiv.className = 'message ' + type;
            setTimeout(() => {
                messageDiv.textContent = '';
                messageDiv.className = '';
            }, 3000);
        }

        // Show add product message
        function showAddMessage(text, type) {
            const messageDiv = document.getElementById('addMessage');
            messageDiv.textContent = text;
            messageDiv.className = 'message ' + type;
            setTimeout(() => {
                messageDiv.textContent = '';
                messageDiv.className = '';
            }, 3000);
        }

        // Add product
        function addProduct() {
            const name = document.getElementById('productName').value.trim();
            const price = parseFloat(document.getElementById('productPrice').value);
            const category = document.getElementById('productCategory').value.trim();
            const description = document.getElementById('productDescription').value.trim();

            if (!name) {
                showAddMessage('Please enter product name', 'error');
                return;
            }

            if (isNaN(price) || price < 0) {
                showAddMessage('Please enter a valid price', 'error');
                return;
            }

            const product = {
                id: Date.now(),
                name: name,
                price: price,
                category: category || 'Uncategorized',
                description: description,
                dateAdded: new Date().toLocaleDateString()
            };

            products.push(product);
            saveToLocalStorage();
            renderProducts();
            updateStats();
            
            // Clear form
            document.getElementById('productName').value = '';
            document.getElementById('productPrice').value = '';
            document.getElementById('productCategory').value = '';
            document.getElementById('productDescription').value = '';

            showAddMessage('Product added successfully!', 'success');
        }

        // Delete product
        function deleteProduct(id) {
            if (confirm('Are you sure you want to delete this product?')) {
                products = products.filter(p => p.id !== id);
                saveToLocalStorage();
                renderProducts();
                updateStats();
                showAddMessage('Product deleted!', 'success');
            }
        }

        // Render products
        function renderProducts() {
            const productsList = document.getElementById('productsList');
            
            if (products.length === 0) {
                productsList.innerHTML = '<p style="color: #999; text-align: center; padding: 40px 0;">No products added yet</p>';
                return;
            }

            productsList.innerHTML = products.map(product => `
                <div class="product-item">
                    <div class="product-info">
                        <h3>${product.name}</h3>
                        <p><strong>Category:</strong> ${product.category}</p>
                        <p><strong>Added:</strong> ${product.dateAdded}</p>
                        ${product.description ? `<p><strong>Note:</strong> ${product.description}</p>` : ''}
                    </div>
                    <div style="text-align: right;">
                        <div class="product-price">$${product.price.toFixed(2)}</div>
                        <div class="product-actions" style="margin-top: 10px;">
                            <button class="btn btn-small delete-btn" onclick="deleteProduct(${product.id})">Delete</button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Update statistics
        function updateStats() {
            const total = products.length;
            const totalValue = products.reduce((sum, p) => sum + p.price, 0);
            const averagePrice = total > 0 ? totalValue / total : 0;

            document.getElementById('totalProducts').textContent = total;
            document.getElementById('totalValue').textContent = '$' + totalValue.toFixed(2);
            document.getElementById('averagePrice').textContent = '$' + averagePrice.toFixed(2);
        }

        // Local storage functions
        function saveToLocalStorage() {
            localStorage.setItem('products', JSON.stringify(products));
        }

        function loadFromLocalStorage() {
            const stored = localStorage.getItem('products');
            const storedCode = localStorage.getItem('appSecretCode');
            
            if (stored) {
                products = JSON.parse(stored);
            }

            if (storedCode) {
                secretCode = storedCode;
                document.getElementById('secretCode').textContent = secretCode;
            }
        }

        // Logout
        function logout() {
            isLoggedIn = false;
            document.getElementById('appScreen').style.display = 'none';
            document.getElementById('loginScreen').style.display = 'flex';
            document.getElementById('codeInput').value = '';
        }
    </script>
</body>
</html>
