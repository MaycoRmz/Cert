<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificate of Completion</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f9f9f9;
        }
        .certificate {
            border: 10px solid #000;
            padding: 20px;
            width: 800px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            position: relative;
        }
        .certificate h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .certificate h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .certificate p {
            font-size: 1.2em;
            margin: 20px 0;
        }
        .header {
            font-family: 'Old English Text MT', serif;
            font-size: 2.2em;
            margin-bottom: 20px;
        }
        .signatures {
            margin-top: 30px;
            display: flex;
            justify-content: space-around;
        }
        .signature {
            text-align: center;
        }
        .signature-line {
            margin-top: 50px;
            border-top: 1px solid #000;
            width: 200px;
        }
        input {
            border: none;
            border-bottom: 1px solid #000;
            text-align: center;
            font-size: 1.2em;
            width: auto;
        }
        .print-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            padding: 10px 20px;
            background: #007bff;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .print-btn:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <div class="certificate">
        <button class="print-btn" onclick="window.print()">Print</button>
        <div class="header">834 Hostess Brands</div>
        <h1>Certificate of Completion</h1>
        <p>This is to certify that</p>
        <h2><input type="text" placeholder="Recipient Name"></h2>
        <p>has successfully completed the</p>
        <h2>Shag Truck Train the Trainer Program</h2>
        <p>on the <input type="text" placeholder="Day"> day of <input type="text" placeholder="Month">, <input type="text" placeholder="Year">.</p>
        <p>Presented by</p>
        <h2>The J.M. Smucker Company</h2>
        <div class="signatures">
            <div class="signature">
                <div class="signature-line"></div>
                <p>Name & Title</p>
            </div>
            <div class="signature">
                <div class="signature-line"></div>
                <p>Name & Title</p>
            </div>
        </div>
    </div>
</body>
</html>

