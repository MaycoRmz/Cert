<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificate of Completion</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
        }
        .certificate {
            position: relative;
            border: 20px solid #234;
            border-image: linear-gradient(45deg, #234, #567) 1;
            padding: 40px;
            width: 800px;
            background: #fff;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            text-align: center;
        }
        .corner {
            position: absolute;
            width: 50px;
            height: 50px;
            border: 3px solid #456;
        }
        .top-left {
            top: 10px;
            left: 10px;
            border-right: none;
            border-bottom: none;
        }
        .top-right {
            top: 10px;
            right: 10px;
            border-left: none;
            border-bottom: none;
        }
        .bottom-left {
            bottom: 10px;
            left: 10px;
            border-right: none;
            border-top: none;
        }
        .bottom-right {
            bottom: 10px;
            right: 10px;
            border-left: none;
            border-top: none;
        }
        .certificate h1 {
            font-size: 3em;
            margin-bottom: 20px;
            color: #234;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        .certificate h2 {
            font-size: 1.8em;
            margin: 15px 0;
            color: #456;
        }
        .certificate p {
            font-size: 1.3em;
            margin: 20px 0;
            color: #333;
            line-height: 1.6;
        }
        .logo {
            margin-bottom: 30px;
            position: relative;
        }
        .logo::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 180px;
            height: 180px;
            background: radial-gradient(circle, rgba(255,255,255,0.8) 0%, rgba(255,255,255,0) 70%);
            z-index: 1;
        }
        .logo img {
            position: relative;
            z-index: 2;
        }
        .signatures {
            margin-top: 50px;
            display: flex;
            justify-content: space-around;
            padding: 0 40px;
        }
        .signature {
            text-align: center;
            flex: 1;
            margin: 0 20px;
        }
        .signature-line {
            margin-top: 60px;
            border-top: 2px solid #456;
            width: 100%;
            position: relative;
        }
        .signature-line::after {
            content: '';
            position: absolute;
            bottom: 5px;
            left: 0;
            width: 100%;
            height: 1px;
            background: rgba(69, 85, 102, 0.3);
        }
        .date-line {
            border-bottom: 2px solid #456;
            display: inline-block;
            width: 150px;
            margin: 0 10px;
        }
        .certificate::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M50 50h-40v40h40z' fill='%23234' fill-opacity='0.02'/%3E%3C/svg%3E");
            pointer-events: none;
        }
        .company-name {
            font-size: 1.6em;
            margin: 15px 0;
            color: #456;
        }
        @media print {
            body {
                background: none;
            }
            .certificate {
                box-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="certificate">
        <div class="corner top-left"></div>
        <div class="corner top-right"></div>
        <div class="corner bottom-left"></div>
        <div class="corner bottom-right"></div>
        <div class="logo">
            <img src="/api/placeholder/150/150" alt="Hostess Brands Logo">
        </div>
        <h1>Certificate of Completion</h1>
        <p>This is to certify that</p>
        <h2>_______________________________</h2>
        <p>has successfully completed the</p>
        <h2>Shag Truck Train the Trainer Program</h2>
        <p>on the <span class="date-line"></span> day of <span class="date-line"></span>, <span class="date-line"></span></p>
        <p>Presented by</p>
        <div class="company-name">
            Hostess Brands,<br>
            a J.M. Smucker Company
        </div>
        <div class="signatures">
            <div class="signature">
                <div class="signature-line"></div>
                <p>Program Director</p>
            </div>
            <div class="signature">
                <div class="signature-line"></div>
                <p>Training Supervisor</p>
            </div>
        </div>
    </div>
</body>
</html>
