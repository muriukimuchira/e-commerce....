# e-commerce....<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>E-Commerce Product Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 30px;
      background-color: #f4f4f9;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    th, td {
      padding: 15px;
      text-align: left;
      border-bottom: 1px solid #ddd;
      vertical-align: top;
    }

    th {
      background-color: #0077cc;
      color: white;
    }

    img.icon {
      width: 40px;
      height: 40px;
      border-radius: 50%;
    }

    ul {
      padding-left: 18px;
      margin: 0;
    }

    tr:hover {
      background-color: #f1f1f1;
    }

    .category {
      font-weight: bold;
      color: #555;
    }
  </style>
</head>
<body>

  <h2>E-Commerce Product Listing</h2>

  <table>
    <thead>
      <tr>
        <th>E-Commerce Firm</th>
        <th>Icon</th>
        <th>Product Name</th>
        <th>Product Category</th>
        <th>Product Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Amazon</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon"></td>
        <td>Echo Dot</td>
        <td class="category">Electronics</td>
        <td>
          <ul>
            <li>Smart speaker with Alexa</li>
            <li>Voice control music</li>
            <li>Compact and powerful</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Flipkart</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flipkart_logo.png" alt="Flipkart"></td>
        <td>Realme Narzo 50</td>
        <td class="category">Mobile Phones</td>
        <td>
          <ul>
            <li>6.6" Display</li>
            <li>Helio G96 Processor</li>
            <li>5000 mAh Battery</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>eBay</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/1/1b/EBay_logo.svg" alt="eBay"></td>
        <td>Canon EOS M50</td>
        <td class="category">Camera</td>
        <td>
          <ul>
            <li>24.1 MP Mirrorless</li>
            <li>Dual Pixel Autofocus</li>
            <li>4K Video Recording</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Amazon</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon"></td>
        <td>Kindle Paperwhite</td>
        <td class="category">Books & Media</td>
        <td>
          <ul>
            <li>High-resolution display</li>
            <li>Built-in light</li>
            <li>Waterproof</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Flipkart</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flipkart_logo.png" alt="Flipkart"></td>
        <td>Boat Rockerz 255</td>
        <td class="category">Audio</td>
        <td>
          <ul>
            <li>Bluetooth earphones</li>
            <li>IPX5 water-resistant</li>
            <li>Fast charging</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Myntra</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/e/e5/Myntra_logo.png" alt="Myntra"></td>
        <td>HRX Men’s Jacket</td>
        <td class="category">Apparel</td>
        <td>
          <ul>
            <li>Regular fit</li>
            <li>Full sleeves</li>
            <li>Machine washable</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Ajio</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/6/6f/AJIO_Logo.png" alt="Ajio"></td>
        <td>Lee Cooper Sneakers</td>
        <td class="category">Footwear</td>
        <td>
          <ul>
            <li>Cushioned sole</li>
            <li>Lace-up design</li>
            <li>Durable outsole</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Nykaa</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/3/30/Nykaa_logo.png" alt="Nykaa"></td>
        <td>Lakme Lipstick</td>
        <td class="category">Beauty</td>
        <td>
          <ul>
            <li>Matte finish</li>
            <li>Long-lasting color</li>
            <li>Rich pigmentation</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>BigBasket</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/4/45/Bigbasket_logo.png" alt="BigBasket"></td>
        <td>Organic Tomatoes</td>
        <td class="category">Groceries</td>
        <td>
          <ul>
            <li>Freshly harvested</li>
            <li>Pesticide-free</li>
            <li>1 kg pack</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Swiggy Instamart</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/1/12/Swiggy_logo.svg" alt="Swiggy"></td>
        <td>Amul Milk 1L</td>
        <td class="category">Dairy</td>
        <td>
          <ul>
            <li>Full cream</li>
            <li>Pasteurized</li>
            <li>Rich in calcium</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Amazon</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon"></td>
        <td>HP Pavilion Laptop</td>
        <td class="category">Computers</td>
        <td>
          <ul>
            <li>Intel i5 processor</li>
            <li>8GB RAM, 512GB SSD</li>
            <li>Windows 11</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Flipkart</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flipkart_logo.png" alt="Flipkart"></td>
        <td>Samsung 55" TV</td>
        <td class="category">Home Appliances</td>
        <td>
          <ul>
            <li>4K UHD Smart TV</li>
            <li>HDR support</li>
            <li>Multiple HDMI ports</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Ajio</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/6/6f/AJIO_Logo.png" alt="Ajio"></td>
        <td>Pepe Jeans T-Shirt</td>
        <td class="category">Apparel</td>
        <td>
          <ul>
            <li>Cotton fabric</li>
            <li>Graphic print</li>
            <li>Round neck</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Myntra</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/e/e5/Myntra_logo.png" alt="Myntra"></td>
        <td>Fastrack Watch</td>
        <td class="category">Accessories</td>
        <td>
          <ul>
            <li>Analog dial</li>
            <li>Water resistant</li>
            <li>1-year warranty</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Nykaa</td>
        <td><img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/3/30/Nykaa_logo.png" alt="Nykaa"></td>
        <td>L'Oreal Hair Serum</td>
        <td class="category">Beauty</td>
        <td>
          <ul>
            <li>Frizz control</li>
            <li>Non-sticky</li>
            <li>Suitable for all hair types</li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>

</body>
</html>

