<html>
 <head>
  <title>
   A Web Page
  </title>
  <style>
   body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ccc;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 0;
        }
        .header input[type="text"] {
            width: 300px;
            padding: 5px;
        }
        .header img {
            width: 20px;
            height: 20px;
        }
        .nav {
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            border-bottom: 1px solid #ccc;
        }
        .nav a {
            text-decoration: none;
            color: #000;
            padding: 5px 10px;
        }
        .content {
            display: flex;
            padding: 20px 0;
        }
        .content img {
            width: 200px;
            height: 200px;
            border: 1px solid #ccc;
            margin-right: 20px;
        }
        .details {
            flex: 1;
        }
        .details p {
            margin: 10px 0;
        }
        .details input[type="text"], .details select {
            width: 100%;
            padding: 5px;
            margin: 5px 0;
            border: 1px solid #ccc;
        }
        .details input[type="checkbox"] {
            margin-right: 10px;
        }
        .details label {
            display: flex;
            align-items: center;
        }
        .details .checkbox-group {
            margin: 10px 0;
        }
        .details .checkbox-group label {
            margin-right: 20px;
        }
        .details .button {
            text-align: center;
            margin-top: 20px;
        }
        .details .button button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
  </style>
 </head>
 <body>
  <div class="container">
   <div class="header">
    <div>
     <img alt="Browser Icon" height="20" src="https://storage.googleapis.com/a1aa/image/CNC44zomf8xVYiLRNxVfGelxe81JXSafLaNrYmJR80A3TAtcC.jpg" width="20"/>
     <input type="text" value="http://mackbook.id.com"/>
    </div>
    <div>
     <img alt="Search Icon" height="20" src="https://storage.googleapis.com/a1aa/image/nQL1neCeJ1pVi0baxt6elsuPk1PRGa76pkDn7yIXvAo4EQLnA.jpg" width="20"/>
    </div>
   </div>
   <div class="nav">
    <a href="#">
     <strong>Home</strong>
    </a>
    <a href="#">
     <strong>Register</strong>
    </a>
    <a href="#">
     <strong>Policy</strong>
    </a>
    <a href="#">
     <strong>About</strong>
    </a>
   </div>
   <div class="content">
    <img src="Images/Gambar mackbook.jpg" height="200"  width="200"/>
    <div class="details">
     <p>
      <strong>Title Here:</strong> MacBook M1 Pro
     </p>
     <p>
      <strong>Description:</strong>MacBook Pro 14 inci dengan prosesor M1 Pro memiliki CPU 10-core, GPU 16-core, dan neural engine 16-core. Chip M1 Pro memiliki mesin media khusus enkode dan dekode yang mendukung codec H.264, HEVC, dan ProRes. Untuk performa lebih stabil, MacBook Pro dibekali sistem termal yang bisa menyuplai udara 50% lebih banyak.
     </p>
     <p>
      <strong>Year:</strong> 2020
     </p>
     <p>
      <strong>Model:</strong> M1 Pro
     </p>
     <p>
      <strong>Condition:</strong> Masih mulus
     </p>
     <p>
      <strong>Total Amount:</strong> 10.000.000
     </p>
     <p>
      <strong>Pay to:</strong> 01120242205
     </p>
     <p>
      <strong>Payment Type:</strong>
      <select>
       <option>Visa Debit</option>
       <option>BCA</option>
       <option>BNI</option>
      </select>
     </p>
     <p>
      <strong>Account Holder:</strong>
      <input type="text" value="Name Here"/>
     </p>
     <p>
      <strong>Account No:</strong>
      <br>
      <input type="number" value="123"/>
     </p>
     <div class="checkbox-group">
      <label>
       <input checked="" type="checkbox"/>
       Send to Mobile Phone
      </label>
      <label>
       <input checked="" type="checkbox"/>
       Email me copy of transaction
      </label>
     </div>
     <p>
      <strong>Send to Mobile Phone:</strong>
      <br>
      <input type="number" value="089602134851"/>
     </p>
     <p>
      <strong>Send to Email:</strong>
      <input type="text" value="xaviersadek4@gmail.com"/>
     </p>
     <div class="button">
      <button>
       Pay using QuidLink
      </button>
     </div>
    </div>
   </div>
  </div>
 </body>
</html>
