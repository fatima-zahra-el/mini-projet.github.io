# mini-projet.github.io
site HTML/CSS/JS .

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z Location Voiture/HOME</title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\logo.png">

    <style>
        body {
    width: 100%;
    margin: 0%;
    position: relative;
    text-align: center;
}

div {
    background-color: #f6e5d0;
    width: 100%;
    margin: 0%;

}

#myVideo {
    width: 100%;
    margin-bottom: 0%;
    min-width: 100%;
    min-height: 100%;

}

header {
    display: flex;
    justify-content: space-around;
    text-align: center;
    height: 2cm;
}

h2{
    color: #33471d ;
}

button:hover {
    transform: scale(1.2);
}

#all1 {
    display: flex;
    justify-content: space-around;
    margin:0% ;
    padding-top: 1cm;
    

}

#all2 {
    display: flex;
    justify-content: space-around;
    
    
    
}

#all3 {
    display: flex;
    justify-content: space-around;
    padding-bottom: 1cm;
    
}

.tomo {
    padding: 3mm;
    margin: 1mm;
    border: 1mm solid rgb(0, 0, 0);
    border-radius: 20px;
    box-shadow: 10px 10px 10px rgb(0, 0, 0);
    text-align: center;
    width: 10cm;

}

img:hover {
    transform: scale(1.2);
}

img {
    box-shadow: 4px 10px 4px rgb(0, 0, 0);
}

button {
    box-shadow: 4px 4px 10px rgb(0, 0, 0);
}

.info {
    border: 1mm solid black;
    border-radius: 50px;
    height: 1cm;
    background-color: #a4a494;

}

a:hover {
    color: black;
}

a {
    color: white;
    text-shadow: 4px 4px 10px rgb(0, 0, 0);
}

#form {
    border: 1mm solid black;
    text-align: left;
    background-color: #a4a494;
    height: 1cm;
    text-align: left;
}
    </style>
</head>

<body>
    <header style="background-color: #33471d ;">
        <p><a href="#all1">Collections</a></p>
        <p><a href="#info">Sur le site</a></p>
        <p><a href="#contact">Contact</a></p>

    </header>

    <video autoplay muted loop preload="auto" id="myVideo">
        <source src="c:\Users\HP\Videos\LOCATION DE VOITURE.mp4" type="video/mp4">
    </video>


    <div id="all1">
        <div class="tomo">
            <img src="https://www.dacia.m-automotiv.ma/storage/galerie-modeles/July2024/KqnxeL6x75Ykc4r6Us0P.webp"
                alt="dclog" style="width: 300px  ; border-radius: 500px;">
            <h2>Dacia LOGAN</h2>
            <h3>PRIX : 300DH - 500DH / JOUR </h3>
            <button class="info"><a href="file:///C:/Users/HP/Documents/classproject1.html">cliquer ici pour plus
                    d'infos</a></button>
        </div>


        <div class="tomo">
            <img src="https://www.dacianmag.com/pub/media/wysiwyg/Dacia_Duster_facelift-18.jpg" alt="dcdust"
                style="width: 300px; border-radius: 500px;">
            <h2>Dacia Duster</h2>
            <h3>PRIX : 450DH - 700DH / JOUR </h3>
            <button class="info"><a href="file:///C:/Users/HP/Documents/calssproject2.html">cliquer ici pour plus
                    d'infos</a></button>
        </div>
    </div>

    <div id="all2">
        <div class="tomo">
            <img src="https://sf2.autoplus.fr/wp-content/uploads/autoplus/2020/01/hyundai-i10-1-0-eco-intuitive-2020.jpg"
                alt="hyun" style="width: 300px; border-radius: 500px;">
            <h2>Hyundai i10</h2>
            <h3>PRIX : 330 DH / JOUR </h3>
            <button class="info"><a href="file:///C:/Users/HP/Documents/classproject3.html">cliquer ici pour plus
                    d'infos</a></button>
        </div>

        <div class="tomo">
            <img src="https://www.click2move.be/623810-large_default/renault-clio.jpg" alt="renau"
                style="width: 300px; border-radius: 500px;">
            <h2>Renault Clio</h2>
            <h3>PRIX : 385 DH / JOUR </h3>
            <button class="info"><a href="file:///C:/Users/HP/Documents/classproject4.html">cliquer ici pour plus
                    d'infos</a></button>
        </div>
    </div>

    <div id="all3">

        <div class="tomo">
            <img src="https://www.topgear.com/sites/default/files/2024/12/hyundai-tucson-ultimate-17.jpg" alt="hyuntuc"
                style="width: 300px; border-radius: 500px;">
            <h2>Hyundai Tucson</h2>
            <h3>PRIX : 770 DH / JOUR </h3>
            <button class="info"><a href="file:///C:/Users/HP/Documents/classproject5.html">cliquer ici pour plus
                    d'infos</a></button>
        </div>
    </div>
    <section id="info" style="background-color: #a4a494; padding: 3cm; text-align: center; height: 6cm; ">
        <h1>Sur notre site :</h1>
        <h4>Nous vous proposons un large choix de voitures de location adaptées à tous vos besoins, allant des citadines
            économiques aux SUV haut de gamme, avec des tarifs compétitifs, des informations détaillées sur chaque
            véhicule et une réservation simple et rapide.
            Ce site est une agence de location voiture partout au Maroc , votre location ce passe celon votre choix
            de voiture
            , sa couleur et votre budgets convenable </h4>
    </section>



    <footer id="contact" style="background-color: #33471d; padding: 1mm; height: 5cm; text-align: center;">
        <h1>Contacter-Nous ici :</h1>
        <a href="mailto:fatimazahrakouissy@gmail.com">Contacter notre e-mail au cas de probléme.</a>
        <br><br>
        &copy;2026
    </footer>

</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z location Dacia logan/info </title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\Screenshots\logo.png">


    <style>
        h3 {
            text-align: center;
            color: white;
            text-shadow: 10px 10px 10px black;
            margin: 10%;


        }

        a:hover {
            color: black;
        }

        footer {
            color: white;
        }

        table,
        td,
        th {
            border: 1mm solid rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            width: 5cm;
        }

        th {
            color: rgb(156, 154, 154);
        }

        table:hover {
            transform: scale(1.1);
        }

        form {
            border: 1mm solid black;
            border-radius: 10px;
            box-shadow: 10px 10px 10px 10px rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            padding: 1.5mm;
            margin: 6mm;
            background-color: #33471d;
            width: 15cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        body {
            text-align: center;
            background-color: #f6e5d0;
            text-align: center;
            width: 100%;
            background-position: 50% 50%;
        }

        label {
            color: rgb(0, 0, 0);

            text-shadow: 4px 4px 10px rgb(247, 247, 247);
        }
         input , textarea {
            width: 6cm;
            height: 1cm;
        }

        h1,
        h3 {
            color: black;
            text-align: center;

        }

        img {
            width: 8cm;
            display: flexbox;
            height: 7cm;
            margin: 1cm;
        }

        img:hover {
            transform: scale(1.2);
        }

       
    </style>
</head>

<body>
    <h1 style=" color: #33471d;">DACIA LOGAN </h1>
    <section style="border: 1mm solid black; background-color: #33471d;">
        <h1 style="color: #a4a494;">Couleur Disponible :</h1>
        <img src="c:\Users\HP\Downloads\Рестайлинговый Dacia Logan 3 появится в 2025 году.jpg" alt="1">
        <img src="c:\Users\HP\Downloads\Dacia Logan III — Wikipédia.jpg" alt="2">
        <img src="c:\Users\HP\Downloads\Dacia Logan 2008-12.jpg" alt="3">
        <br>
        <button style="width: 4cm ; height: 1cm; background-color: #f6e5d0; margin-right: 3cm; margin-top: 1cm;"><a
                href="#form">Réserver</a></button>
    </section>



    <section style="border: 1mm solid black; background-color: #f6e5d0;">
        <h1 style="color: #33471d;">Informations mécanique :</h1>
        <h3>La Dacia Logan est une berline compacte robuste, idéale pour la conduite urbaine et les trajets
            inter-urbains.
            Consommation modérée, facile à garer, coffre généreux et coût d’entretien faible : elle est très prisée pour
            les
            séjours touristiques ou les déplacements quotidiens au Maroc.
            Son moteur peut être essence ou diesel selon disponibilité.
            <br><br>
            💸 Prix indicatifs:<br>
            Rabat : ~396–500 MAD/jour . <br>
            Marrakech : ~300–500 MAD/jour . <br>
            Agadir : ~390–500 MAD/jour . <br>
            Nador : ~396–500 MAD/jour . <br>
            <br>
            <table>
                <tr>
                    <th>Modèle</th>
                    <td>Dacia Logan</td>
                </tr>
                <tr>
                    <th>Catégorie</th>
                    <td>citadine\compacte</td>
                </tr>
                <tr>
                    <th>Kilométrage</th>
                    <td>~30 000–60 000 km</td>
                </tr>
                <tr>
                    <th>Carburant</th>
                    <td>Essence / Diesel</td>
                </tr>
            </table>
        </h3>
    </section>


    <section style="background-color: #a4a494; padding-bottom: 1cm; padding-top: 1cm; border: 1mm solid black">
        <h1 id="reserver" style="color: #f6e5d0;">Réserver :</h1>
        <form>
            <h1 style="color: #f6e5d0; text-shadow: 4px 4px 10px  black" id="form">Formulaire :</h1>
            <br>
            <label for="name">Entrez votre Nom:</label>
            <br>
            <br>
            <input type="text" name="name" id="name" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="prname">Entrez votre Prénom:</label>
            <br>
            <br>
            <input type="text" name="prname" id="prname" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="age">Entrez votre Age:</label>
            <br>
            <br>
            <input type="number" name="age" id="age" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="permis">Entrez votre photo Permis:</label>
            <br>
            <br>
            <input type="file" name="permis" id="permis">
            <br><br>
            <label for="choix">Entrez votre Voiture choisie:</label>
            <br>
            <br>
            <select>
                <option value="Dacia LOGAN">Dacia LOGAN</option>
                <option value="Dacia Duster">Dacia Duster</option>
                <option value="Hyundai i10">Hyundai i10</option>
                <option value="Renault Clio">Renault Clio</option>
                <option value="Hyundai Tucson">Hyundai Tucson</option>
            </select>
            <br><br>
            <label for="choix">Entrez votre Couleur choisie:</label>
            <br>
            <br>
            <input type="color" alt="clr" name="clr" id="clr">
            <br><br>
            <label for="adresse">Entrez votre Adresse de location:</label>
            <br>
            <br>
            <input type="text" name="adresse" id="adresse" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="date">Entrez votre Date pour location:</label>
            <br>
            <br>
            <input type="date" name="date" id="date">
            <br><br>
            <label for="tele">Entrez votre Num Téléphone:</label>
            <br>
            <br>
            <input type="tel" name="tele" id="tele" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="mail">Entrez votre E-mail:</label>
            <br>
            <br>
            <input type="email" name="mail" id="mail" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="cmnt">Commentaires :</label>
            <br>
            <br>
            <textarea name="cmnt" id="cmnt"> </textarea>
            <br><br><br>
            <button id="ok">ENVOYER</button>

        </form>
    </section>


    <script>
        document.getElementById("ok").onclick = function () {
            alert(" 👍 Votre Formulaire est Envoyer !");
        };
    </script>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z location Hyundai i10/info</title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\Screenshots\logo.png">

    <style>
        h3 {
            text-align: center;
            color: white;
            text-shadow: 10px 10px 10px black;
            margin: 10%;


        }

        a:hover {
            color: black;
        }

        footer {
            color: white;
        }

        table,
        td,
        th {
            border: 1mm solid rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            width: 5cm;
        }

        th {
            color: rgb(156, 154, 154);
        }

        table:hover {
            transform: scale(1.1);
        }

       form {
            border: 1mm solid black;
            border-radius: 10px;
            box-shadow: 10px 10px 10px 10px rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            padding: 1.5mm;
            margin: 6mm;
            background-color: #33471d;
            width: 15cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        body {
            text-align: center;
            background-color: #f6e5d0;
            text-align: center;
            width: 100%;
            background-position: 50% 50%;
        }

        label {
            color: rgb(0, 0, 0);

            text-shadow: 4px 4px 10px rgb(247, 247, 247);
        }
         input , textarea {
            width: 6cm;
            height: 1cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        h1,
        h3 {
            color: black;
            text-align: center;

        }

        img {
            width: 8cm;
            display: flexbox;
            height: 7cm;
            margin: 1cm;
        }

        img:hover {
            transform: scale(1.2);
        }
    </style>

</head>

<body>
    <h1 style="color: #33471d;"> HYUNDAI i10 </h1>

    <section style="border: 1mm solid black; background-color: #33471d;">
        <h1 style="color: #a4a494;">Couleur Disponible :</h1>
        <img src="c:\Users\HP\Downloads\Hyundai i10 N-Line_ Imagen mas deportiva y motor turbo de 100 CV.jpg" alt="1">
        <img src="c:\Users\HP\Downloads\Hyundai i10.jpg" alt="2">
        <img src="c:\Users\HP\Downloads\Hyundai Grand i10 Sedan - ZA version.jpg" alt="3">
        <br>
        <button style="width: 4cm ; height: 1cm; background-color: #f6e5d0; margin-right: 3cm; margin-top: 1cm;"><a
                href="#form">Réserver</a></button>
    </section>

    <section style="border: 1mm solid black; background-color: #f6e5d0;">
        <h1 style="color: #33471d;">Informations mécanique :</h1>
        <h3>La Hyundai i10 est une citadine agile, économique en carburant, parfaite pour la circulation urbaine et les
            courts trajets. Elle offre un bon compromis entre confort et prix pour les visiteurs qui n’ont pas besoin
            d’une
            grande voiture.

            <br> <br> 💸 Prix observés: <br>

            Tous les villes : 330 MAD / jour . <br>
            <br>
            <table>
                <tr>
                    <th>Modèle</th>
                    <td>Hyundai i10</td>
                </tr>
                <tr>
                    <th>Catégorie</th>
                    <td>Citadine</td>
                </tr>
                <tr>
                    <th>Kilométrage</th>
                    <td>~20 000–40 000 km</td>
                </tr>
                <tr>
                    <th>Carburant</th>
                    <td>Essence </td>
                </tr>
            </table>
        </h3>
    </section>

     <section style="background-color: #a4a494; padding-bottom: 1cm; padding-top: 1cm; border: 1mm solid black">
            <h1 id="reserver" style="color: #f6e5d0;">Réserver :</h1>
            <form>
                <h1 style="color: #f6e5d0; text-shadow: 4px 4px 10px  black" id="form">Formulaire :</h1>
                <br>
                <label for="name">Entrez votre Nom:</label>
                <br><br>
                <input type="text" name="name" id="name" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="prname">Entrez votre Prénom:</label>
                <br>
                <input type="text" name="prname" id="prname" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="age">Entrez votre Age:</label>
                <br><br>
                <input type="number" name="age" id="age" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="permis">Entrez votre photo Permis:</label>
                <br><br>
                <input type="file" name="permis" id="permis">
                <br><br>
                <label for="choix">Entrez votre Voiture choisie:</label>
                <br><br>
                <select>
                    <option value="Dacia LOGAN">Dacia LOGAN</option>
                    <option value="Dacia Duster">Dacia Duster</option>
                    <option value="Hyundai i10">Hyundai i10</option>
                    <option value="Renault Clio">Renault Clio</option>
                    <option value="Hyundai Tucson">Hyundai Tucson</option>
                </select>
                <br><br>
                <label for="choix">Entrez votre Couleur choisie:</label>
                <br><br>
                <input type="color" alt="clr" name="clr" id="clr">
                <br><br>
                <label for="adresse">Entrez votre Adresse de location:</label>
                <br><br>
                <input type="text" name="adresse" id="adresse" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="date">Entrez votre Date pour location:</label>
                <br><br>
                <input type="date" name="date" id="date">
                <br><br>
                <label for="tele">Entrez votre Num Téléphone:</label>
                <br><br>
                <input type="tel" name="tele" id="tele" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="mail">Entrez votre E-mail:</label>
                <br><br>
                <input type="email" name="mail" id="mail" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="cmnt">Commentaires :</label>
                <br><br>
                <textarea name="cmnt" id="cmnt"> </textarea>
                <br><br><br>
                <button id="ok">ENVOYER</button>

            </form>
        </section>


        <script>
            document.getElementById("ok").onclick = function () {
                alert(" 👍 Votre Formulaire est Envoyer !");
            };
        </script>

</body>

</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z location Renault Clio/info </title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\Screenshots\logo.png">

    <style>
        h3 {
            text-align: center;
            color: white;
            text-shadow: 10px 10px 10px black;
            margin: 10%;


        }

        a:hover {
            color: black;
        }

        footer {
            color: white;
        }

        table,
        td,
        th {
            border: 1mm solid rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            width: 5cm;
        }

        th {
            color: rgb(156, 154, 154);
        }

        table:hover {
            transform: scale(1.1);
        }

       form {
            border: 1mm solid black;
            border-radius: 10px;
            box-shadow: 10px 10px 10px 10px rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            padding: 1.5mm;
            margin: 6mm;
            background-color: #33471d;
            width: 15cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        body {
            text-align: center;
            background-color: #f6e5d0;
            text-align: center;
            width: 100%;
            background-position: 50% 50%;
        }

        label {
            color: rgb(0, 0, 0);

            text-shadow: 4px 4px 10px rgb(247, 247, 247);
        }
         input , textarea {
            width: 6cm;
            height: 1cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        h1,
        h3 {
            color: black;
            text-align: center;

        }

        img {
            width: 8cm;
            display: flexbox;
            height: 7cm;
            margin: 1cm;
        }

        img:hover {
            transform: scale(1.2);
        }
    </style>

</head>

<body>
    <h1 style="color: #33471d;"> RENAULT CLIO </h1>

    <section style="border: 1mm solid black; background-color: #33471d;">
        <h1 style="color: #a4a494;">Couleur Disponible :</h1>

        <img src="c:\Users\HP\Downloads\Renault Clio - red passion.jpg" alt="1">
        <img src="c:\Users\HP\Downloads\Used CLIO RENAULT 1_2 16V Dynamique Nav 5dr 2016….jpg" alt="2">
        <img src="c:\Users\HP\Downloads\Renault Clio Narrowly Beats VW Golf To Become Europe’s Best-Selling Car _ Carscoops.jpg" alt="3">
        <br>
        <button style="width: 4cm ; height: 1cm; background-color: #f6e5d0; margin-right: 3cm; margin-top: 1cm;"><a
                href="#form">Réserver</a></button>
    </section>

    <section style="border: 1mm solid black; background-color: #f6e5d0;">
        <h1 style="color: #33471d;">Informations mécanique :</h1>
        <h3>
            La Renault Clio est une compacte confortable, un peu plus spacieuse qu’une petite citadine, adaptée aux
            déplacements urbains et routiers. Elle offre une meilleure dynamique de conduite sans coûter beaucoup plus
            qu’une citadine.

            <br> <br> 💸 Prix observés: <br>

            Tous les villes :385 MAD / jour . <br>
            <br>
            <table>
                <tr>
                    <th>Modèle</th>
                    <td>Renault Clio</td>
                </tr>
                <tr>
                    <th>Catégorie</th>
                    <td>Compacte</td>
                </tr>
                <tr>
                    <th>Kilométrage</th>
                    <td>~30 000–60 000 km</td>
                </tr>
                <tr>
                    <th>Carburant</th>
                    <td>Essence\Diesel </td>
                </tr>
            </table>
        </h3>
    </section>

     <section style="background-color: #a4a494; padding-bottom: 1cm; padding-top: 1cm; border: 1mm solid black">
            <h1 id="reserver" style="color: #f6e5d0;">Réserver :</h1>
            <form>
                <h1 style="color: #f6e5d0; text-shadow: 4px 4px 10px  black" id="form">Formulaire :</h1>
                <br>
                <label for="name">Entrez votre Nom:</label>
                <br><br>
                <input type="text" name="name" id="name" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="prname">Entrez votre Prénom:</label>
                <br>
                <input type="text" name="prname" id="prname" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="age">Entrez votre Age:</label>
                <br><br>
                <input type="number" name="age" id="age" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="permis">Entrez votre photo Permis:</label>
                <br><br>
                <input type="file" name="permis" id="permis">
                <br><br>
                <label for="choix">Entrez votre Voiture choisie:</label>
                <br><br>
                <select>
                    <option value="Dacia LOGAN">Dacia LOGAN</option>
                    <option value="Dacia Duster">Dacia Duster</option>
                    <option value="Hyundai i10">Hyundai i10</option>
                    <option value="Renault Clio">Renault Clio</option>
                    <option value="Hyundai Tucson">Hyundai Tucson</option>
                </select>
                <br><br>
                <label for="choix">Entrez votre Couleur choisie:</label>
                <br><br>
                <input type="color" alt="clr" name="clr" id="clr">
                <br><br>
                <label for="adresse">Entrez votre Adresse de location:</label>
                <br><br>
                <input type="text" name="adresse" id="adresse" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="date">Entrez votre Date pour location:</label>
                <br><br>
                <input type="date" name="date" id="date">
                <br><br>
                <label for="tele">Entrez votre Num Téléphone:</label>
                <br><br>
                <input type="tel" name="tele" id="tele" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="mail">Entrez votre E-mail:</label>
                <br><br>
                <input type="email" name="mail" id="mail" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="cmnt">Commentaires :</label>
                <br><br>
                <textarea name="cmnt" id="cmnt"> </textarea>
                <br><br><br>
                <button id="ok">ENVOYER</button>

            </form>
        </section>


        <script>
            document.getElementById("ok").onclick = function () {
                alert(" 👍 Votre Formulaire est Envoyer !");
            };
        </script>

</body>

</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z location Hyundai Tucson/info </title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\Screenshots\logo.png">

    <style>
        h3 {
            text-align: center;
            color: white;
            text-shadow: 10px 10px 10px black;
            margin: 10%;


        }

        a:hover {
            color: black;
        }

        footer {
            color: white;
        }

        table,
        td,
        th {
            border: 1mm solid rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            width: 5cm;
        }

        th {
            color: rgb(156, 154, 154);
        }

        table:hover {
            transform: scale(1.1);
        }

        form {
            border: 1mm solid black;
            border-radius: 10px;
            box-shadow: 10px 10px 10px 10px rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            padding: 1.5mm;
            margin: 6mm;
            background-color: #33471d;
            width: 15cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        body {
            text-align: center;
            background-color: #f6e5d0;
            text-align: center;
            width: 100%;
            background-position: 50% 50%;
        }

        label {
            color: rgb(0, 0, 0);

            text-shadow: 4px 4px 10px rgb(247, 247, 247);
        }
         input , textarea {
            width: 6cm;
            height: 1cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

       

        h1,
        h3 {
            color: black;
            text-align: center;

        }

        img {
            width: 8cm;
            display: flexbox;
            height: 7cm;
            margin: 1cm;
        }

        img:hover {
            transform: scale(1.2);
        }
    </style>


</head>

<body>
    <h1 style="color: #33471d;"> HUNDAI TUCSON</h1>
    <section style="border: 1mm solid black; background-color: #33471d;">
        <h1 style="color: #a4a494;">Couleur Disponible :</h1>

        <img src="c:\Users\HP\Downloads\Hyundai Tucson Plug-in Hybrid 2022.jpg" alt="1">
        <img src="c:\Users\HP\Downloads\2026 Hyundai Tucson_ Key Specs at a Glance _ en_wheelz.me" alt="2">
        <img src="c:\Users\HP\Downloads\Hyundai Tucson 4WD Launched, Priced At Rs_ 25.19 Lakhs _ MotorBeam" alt="3">
        <br>
        <button style="width: 4cm ; height: 1cm; background-color: #f6e5d0; margin-right: 3cm; margin-top: 1cm;"><a
                href="#form">Réserver</a></button>
    </section>

    <section style="border: 1mm solid black; background-color: #f6e5d0;">
        <h1 style="color: #33471d;">Informations mécanique :</h1>
        <h3>
            Le Hyundai Tucson est un SUV milieu de gamme plus confortable et puissant qu’un Dacia Duster. Il convient
            pour
            les longs trajets et les routes montagneuses, offrant plus d’espace et d’équipements.
            <br> <br> 💸 Prix observés: <br>

            Tous les villes :770 MAD / jour . <br>
            <br>
            <table>
                <tr>
                    <th>Modèle</th>
                    <td>Hyundai Tucson</td>
                </tr>
                <tr>
                    <th>Catégorie</th>
                    <td>SUV moyen</td>
                </tr>
                <tr>
                    <th>Kilométrage</th>
                    <td>~15 000–40 000 km</td>
                </tr>
                <tr>
                    <th>Carburant</th>
                    <td>Essence\Diesel </td>
                </tr>
            </table>
        </h3>
    </section>

    <section style="background-color: #a4a494; padding-bottom: 1cm; padding-top: 1cm; border: 1mm solid black">
        <h1 id="reserver" style="color: #f6e5d0;">Réserver :</h1>
        <form>
            <h1 style="color: #f6e5d0; text-shadow: 4px 4px 10px  black" id="form">Formulaire :</h1>
            <br>
            <label for="name">Entrez votre Nom:</label>
            <br><br>
            <input type="text" name="name" id="name" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="prname">Entrez votre Prénom:</label>
            <br>
            <input type="text" name="prname" id="prname" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="age">Entrez votre Age:</label>
            <br><br>
            <input type="number" name="age" id="age" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="permis">Entrez votre photo Permis:</label>
            <br><br>
            <input type="file" name="permis" id="permis">
            <br><br>
            <label for="choix">Entrez votre Voiture choisie:</label>
            <br><br>
            <select>
                <option value="Dacia LOGAN">Dacia LOGAN</option>
                <option value="Dacia Duster">Dacia Duster</option>
                <option value="Hyundai i10">Hyundai i10</option>
                <option value="Renault Clio">Renault Clio</option>
                <option value="Hyundai Tucson">Hyundai Tucson</option>
            </select>
            <br><br>
            <label for="choix">Entrez votre Couleur choisie:</label>
            <br><br>
            <input type="color" alt="clr" name="clr" id="clr">
            <br><br>
            <label for="adresse">Entrez votre Adresse de location:</label>
            <br><br>
            <input type="text" name="adresse" id="adresse" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="date">Entrez votre Date pour location:</label>
            <br><br>
            <input type="date" name="date" id="date">
            <br><br>
            <label for="tele">Entrez votre Num Téléphone:</label>
            <br><br>
            <input type="tel" name="tele" id="tele" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="mail">Entrez votre E-mail:</label>
            <br><br>
            <input type="email" name="mail" id="mail" placeholder="Ecrivez ici ...">
            <br><br>
            <label for="cmnt">Commentaires :</label>
            <br><br>
            <textarea name="cmnt" id="cmnt"> </textarea>
            <br><br><br>
            <button id="ok">ENVOYER</button>

        </form>
    </section>


    <script>
        document.getElementById("ok").onclick = function () {
            alert(" 👍 Votre Formulaire est Envoyer !");
        };
    </script>

</body>

</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>F.Z location Dacia Duster/info</title>
    <link rel="icon" type="x-icon/image" href="c:\Users\HP\Pictures\Screenshots\logo.png">

    <style>
        h3 {
            text-align: center;
            color: white;
            text-shadow: 10px 10px 10px black;
            margin: 10%;


        }

        a:hover {
            color: black;
        }

        footer {
            color: white;
        }

        table,
        td,
        th {
            border: 1mm solid rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            width: 5cm;
        }

        th {
            color: rgb(156, 154, 154);
        }

        table:hover {
            transform: scale(1.1);
        }

        form {
            border: 1mm solid black;
            border-radius: 10px;
            box-shadow: 10px 10px 10px 10px rgb(0, 0, 0);
            text-align: center;
            justify-self: center;
            padding: 1.5mm;
            margin: 6mm;
            background-color: #33471d;
            width: 15cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        body {
            text-align: center;
            background-color: #f6e5d0;
            text-align: center;
            width: 100%;
            background-position: 50% 50%;
        }

        label {
            color: rgb(0, 0, 0);

            text-shadow: 4px 4px 10px rgb(247, 247, 247);
        }
         input , textarea {
            width: 6cm;
            height: 1cm;
        }

        button {
            justify-self: center;
            border: 1mm solid black;
            border-radius: 20px;
            background-color: #a4a494;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            width: 4cm;
            height: 1cm;
            cursor: pointer;
        }

        h1,
        h3 {
            color: black;
            text-align: center;

        }

        img {
            width: 8cm;
            display: flexbox;
            height: 7cm;
            margin: 1cm;
        }

        img:hover {
            transform: scale(1.2);
        }
    </style>

</head>

<body>
    <h1 style="color: #33471d;">DACIA DUSTER </h1>

    <section style="border: 1mm solid black; background-color: #33471d;">
        <h1 style="color: #a4a494;">Couleur Disponible :</h1>
        <img src="c:\Users\HP\Downloads\2020 Dacia Duster Celebration.jpg" alt="1">
        <img src="c:\Users\HP\Downloads\Dacia Duster [2018].jpg" alt="2">
        <img src="c:\Users\HP\Downloads\Noua Dacia Duster Jurney+ 2022 are un pret de 25_400 euro! Este mai scumpa chiar si decat un Hyundai Tucson sau Mazda CX-30 2022 - AUTOLATEST.jpg" alt="3">
        <br>
        <button style="width: 4cm ; height: 1cm; background-color: #f6e5d0; margin-top: 1cm;"><a
                href="#form">Réserver</a></button>
    </section>

    <section style="border: 1mm solid black; background-color: #f6e5d0;">
        <h1 style="color: #33471d;">Informations mécanique :</h1>
        <h3>Le Dacia Duster est un SUV polyvalent très populaire au Maroc : garde au sol confortable pour routes
            variées,
            coffre spacieux et mécanique simple. Il est adapté aux visites de grandes villes comme Casablanca,
            Marrakech, et
            aux circuits vers l’Atlas ou les plages.

            <br> 💸 Prix indicatifs:
            <br>
            Rabat : ~450–700 MAD/jour .
            <br>
            Casablanca : ~580–700 MAD/jour .
            <br>
            Marrakech : ~450–700 MAD/jour .
            <br>
            Fès : ~450 MAD/jour .
            <br>
            Nador : ~580–700 MAD/jour .
            <br>
            <table>
                <tr>
                    <th>Modèle</th>
                    <td>Dacia Duster</td>
                </tr>
                <tr>
                    <th>Catégorie</th>
                    <td>SUV compact</td>
                </tr>
                <tr>
                    <th>Kilométrage</th>
                    <td>~25 000–50 000 km</td>
                </tr>
                <tr>
                    <th>Carburant</th>
                    <td>Essence / Diesel</td>
                </tr>
            </table>
        </h3>
    </section>


     <section style="background-color: #a4a494; padding-bottom: 1cm; padding-top: 1cm; border: 1mm solid black">
            <h1 id="reserver" style="color: #f6e5d0;">Réserver :</h1>
            <form>
                <h1 style="color: #f6e5d0; text-shadow: 4px 4px 10px  black" id="form">Formulaire :</h1>
                <br>
                <label for="name">Entrez votre Nom:</label>
                <br><br>
                <input type="text" name="name" id="name" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="prname">Entrez votre Prénom:</label>
                <br>
                <input type="text" name="prname" id="prname" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="age">Entrez votre Age:</label>
                <br><br>
                <input type="number" name="age" id="age" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="permis">Entrez votre photo Permis:</label>
                <br><br>
                <input type="file" name="permis" id="permis">
                <br><br>
                <label for="choix">Entrez votre Voiture choisie:</label>
                <br><br>
                <select>
                    <option value="Dacia LOGAN">Dacia LOGAN</option>
                    <option value="Dacia Duster">Dacia Duster</option>
                    <option value="Hyundai i10">Hyundai i10</option>
                    <option value="Renault Clio">Renault Clio</option>
                    <option value="Hyundai Tucson">Hyundai Tucson</option>
                </select>
                <br><br>
                <label for="choix">Entrez votre Couleur choisie:</label>
                <br><br>
                <input type="color" alt="clr" name="clr" id="clr">
                <br><br>
                <label for="adresse">Entrez votre Adresse de location:</label>
                <br><br>
                <input type="text" name="adresse" id="adresse" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="date">Entrez votre Date pour location:</label>
                <br><br>
                <input type="date" name="date" id="date">
                <br><br>
                <label for="tele">Entrez votre Num Téléphone:</label>
                <br><br>
                <input type="tel" name="tele" id="tele" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="mail">Entrez votre E-mail:</label>
                <br><br>
                <input type="email" name="mail" id="mail" placeholder="Ecrivez ici ...">
                <br><br>
                <label for="cmnt">Commentaires :</label>
                <br><br>
                <textarea name="cmnt" id="cmnt"> </textarea>
                <br><br><br>
                <button id="ok">ENVOYER</button>

            </form>
        </section>


        <script>
            document.getElementById("ok").onclick = function () {
                alert(" 👍 Votre Formulaire est Envoyer !");
            };
        </script>

</body>

</body>

</html>

