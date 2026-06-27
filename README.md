<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css/style_33.css">
</head>
<body>

    <div class="div-kiri"></div>
    <div class="div-kanan"></div>

    <div class="container-main">
        <div class="content">
            <h3>KKN kolaborasi UDS X UNEJ Sukorejo-Sukowono</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
                Perspiciatis quasi beatae a, voluptas nihil aut rem harum eaque dolorum et aspernatur, 
                adipisci laborum enim? Ad dolorem nihil optio amet, architecto quaerat exercitationem 
                porro aut magni nemo maiores laudantium perferendis repudiandae eaque non excepturi eum id magnam,
                sit officiis voluptate quas quam nulla? Fugit qui vel, delectus explicabo voluptate ea facere sapiente 
                provident id et laboriosam eum consequuntur nam? Modi quibusdam animi consequuntur est perferendis 
                vel iusto suscipit quos velit culpa, 
                exercitationem in cupiditate dolore adipisci quasi nihil eaque quisquam delectus 
                repudiandae, neque explicabo natus ullam. 
                Adipisci atque repudiandae tenetur ut.</p>
        </div>

    <div class="navigasi-kiri">
        <h3>Daftar link artikel</h3>
        <ul>
            <li><a href="#">link artikel 1</a></li>
            <li><a href="#">link artikel 2</a></li>
            <li><a href="#">link artikel 3</a></li>
            <li><a href="#">link artikel 4</a></li>
            <li><a href="#">link artikel 5</a></li>
        </ul>
    </div>

    <div class="navigasi-kanan">
        <h3>Daftar artikel terbaru</h3>
        <h4>Judul artikel</h4>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Labore, laborum similique maiores aperiam,
            adipisci repellendus dignissimos rem deserunt tenetur recusandae autem a incidunt quod asperiores 
            minus provident repudiandae ratione eius?
        </p>
    </div>
    </div>

    <div class="container-card">
        <div class="card">
            <div class="card-header">
                <img src="gambar/WhatsApp Image 2026-06-26 at 00.30.24.jpeg" alt="">
            </div>
            <h4>Judul artikel</h4>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Eligendi quaerat iste et quod explicabo consectetur quo cupiditate veritatis accusantium illo.
            </p>
        </div>

        <div class="card">
            <div class="card-header">
                <img src="gambar/WhatsApp Image 2026-06-26 at 00.30.24.jpeg" alt="">
            </div>
            <h4>Judul artikel</h4>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Eligendi quaerat iste et quod explicabo consectetur quo cupiditate veritatis accusantium illo.
            </p>
        </div>

        <div class="card">
            <div class="card-header">
                <img src="gambar/WhatsApp Image 2026-06-26 at 00.30.24.jpeg" alt="">
            </div>
            <h4>Judul artikel</h4>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Eligendi quaerat iste et quod explicabo consectetur quo cupiditate veritatis accusantium illo.
            </p>
        </div>
    </div>
    
</body>
</html>


body {
    background-color: white;
    background-image: url(../gambar/WhatsApp\ Image\ 2026-06-26\ at\ 00.30.24.jpeg);
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
}
.div-kiri {
    width: 200px;
    height: 100px;
    float: left;
    background-image: url(../gambar/WhatsApp\ Image\ 2026-06-26\ at\ 00.30.24.jpeg);
    background-size: contain;
    background-repeat: no-repeat;
    background-position: left;
    margin-left: 30px;
}
.div-kanan {
    width: 200px;
    height: 100px;
    float: right;
    background-image: url(../gambar/WhatsApp\ Image\ 2026-06-26\ at\ 00.30.24.jpeg);
    background-size: contain;
    background-repeat: no-repeat;
    background-position: right;
    margin-right: 30px;
}
.container-main {
    width: 900px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
}
.content {
    background-color: rgb(247, 240, 232);
    padding: 30px;
}
.navigasi-kiri {
    background-color: rgb(199, 240, 240);
    padding: 30px;
    flex: 1;
}
.navigasi-kanan {
    background-color: rgb(192, 215, 237);
    padding: 30px;
    flex: 1;
}
.container-card {
    width: 900px;
    margin: 30px auto;
    display: flex;
    justify-content: space-between;
}
.card {
    background-color: white;
    padding: 10px;
    box-sizing: border-box;
    width: 30%;
}
.card .card-header img {
    width: 100%;
}
