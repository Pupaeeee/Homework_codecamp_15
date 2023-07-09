### CodeCamp # 15
1. กัญญาภัค ทองคำ
2.homework1
3.- ให้เปลี่ยนสีพื้นหลังส่วน container
 	- มีเงา + ขอบมนเหมือนเดิม
	- รูปต้องต่อสนิทกับ container

4.
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- <meta charset="UTF-8"> -->
    <!-- <meta http-equiv="X-UA-Compatible" content="IE=edge"> -->
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->
    <title>My Card Gallery</title>
    <style>
        * {
            /* block-size: border-box; */
        }
        .card {
            display: inline-block;
            width: 200px;
            margin: 2px;
            box-shadow: 8px 8px 8px silver;
            border-radius: 10px;
        }
        .card img {
            width: 100%;
            border-radius: 5px 5px 0px 0px;
            display: block;
        }
        .container {
            text-align: center;
            background-color: cadetblue;
            padding: 2px 16px ;

        }
        .container h4{
            margin-bottom: 8px;

        }
        .container p{
            margin-top: 5px;
        }
    </style>

</head>
<body>
    <h2>Image Gallery Card</h2>
    <div class="card">
        <img src="https://picsum.photos/id/78/250">
        <div class="container">
            <h4>Nice Picture</h4>
            <p>a beutiful picture</p>
        </div>
    </div>
    <div class="card">
        <img src="https://picsum.photos/id/88/250">
        <div class="container">
            <h4>Nice Picture</h4>
            <p>a beutiful picture</p>
        </div>
    </div>
    <div class="card">
        <img src="https://picsum.photos/id/67/250">
        <div class="container">
            <h4>Nice Picture</h4>
            <p>a beutiful picture</p>
        </div>
    </div>
    <div class="card">
        <img src="https://picsum.photos/id/12/250">
        <div class="container">
            <h4>Nice Picture</h4>
            <p>a beutiful picture</p>
        </div>
    </div>

    
</body>
</html>