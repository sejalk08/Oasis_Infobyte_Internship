# Oasis_Infobyte_Internship
Oasis_Infobyte_Internship_Task1
Landing Page

-------------HTML Code----------------------
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SejalFitness - The best fitness gym in the town</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="utils.css">
</head>

<body class="overflow-x-hidden">
    <div class="container mx-auto">
        <header>
            <nav class="flex justify-between">
                <div class="logo font-bold flex text-blue items-center">SejalFitness</div>
                <ul class="navbar flex items-center">
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact Us</li>
                    <li><button class="btn">Join Now</button></li>
                </ul>
            </nav>
            <hr>
        </header>
        <main class="min-h-screen">
            <section class="section1">
                <div class="flex">
                    <div class="topleft flex flex-col justify-center px-2">
                        <h1 class="my-1 text-center">The best fitness Gym in the town is here</h1>
                        <p class="text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minima suscipit
                            eaque, itaque harum delectus officiis, deleniti libero perspiciatis at eius error animi quae
                            dolorem, enim maxime commodi earum quasi saepe eos nisi dolore non. A accusantium iusto
                            aperiam neque debitis!</p>
                    </div>
                    <div class="topright">
                        <img src="   https://t4.ftcdn.net/jpg/05/06/37/73/240_F_506377339_lhKikl8KZv92nJnSYIKDMWZiyCcewXLp.jpg"
                            alt="">
                    </div>
                </div>
            </section>
            <hr>
            <section class="section2">
                <h1 class="text-center my-2">Pricing</h1>
                <p class="my-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit rem dicta
                    mollitia hic rerum
                    nihil sunt libero illum omnis deserunt laboriosam dolor ullam neque aperiam, distinctio quam,
                    laborum quisquam ex tenetur quod est. Repudiandae sint molestias numquam. Doloribus perferendis,
                    nihil repudiandae recusandae impedit ut aliquam at dignissimos, odit atque debitis!</p>
                <div class="boxes flex justify-center">
                    <div class="box">
                        <h2>Free</h2>
                        <ul>
                            <li class="highlighted">₹0/month</li>
                            <li>10 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup for free</button></li>
                        </ul>
                    </div>
                    <div class="box">
                        <h2>Pro</h2>
                        <ul>
                            <li class="highlighted">₹150/month</li>
                            <li>10 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup Now</button></li>
                        </ul>
                    </div>
                    <div class="box">
                        <h2>Enterprise</h2>
                        <ul>
                            <li class="highlighted">₹500/month</li>
                            <li>10 users included</li>
                            <li>2 GB of storage</li>
                            <li>Email support</li>
                            <li>Help center access</li>
                            <li><button class="btn">Signup Now</button></li>
                        </ul>
                    </div>

                </div>
            </section>
            <hr>
            <section class="section3">
                <h1 class="text-center my-2">Comapre Plans</h1>
                <div class="container plantable">
                    <table class="table text-center">
                      <thead>
                        <tr>
                          <th></th>
                          <th>Free</th>
                          <th>Pro</th>
                          <th>Enterprise</th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr>
                          <th scope="row" class="text-start">Public</th>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                        </tr>
                        <tr>
                          <th scope="row" class="text-start">Private</th>
                         <td>-</td>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                        </tr>
                      </tbody>
              
                      <tbody>
                        <tr>
                          <th scope="row" class="text-start">Permissions</th>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                        </tr>
                        <tr>
                          <th scope="row" class="text-start">Sharing</th>
                         <td>-</td>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                        </tr>
                        <tr>
                          <th scope="row" class="text-start">Unlimited members</th>
                         <td>-</td>
                          <td>Yes</svg></td>
                          <td>Yes</svg></td>
                        </tr>
                        <tr>
                          <th scope="row" class="text-start">Extra security</th>
                         <td>-</td>
                         <td>-</td>
                          <td>Yes</svg></td>
                        </tr>
                      </tbody>
                    </table>
            </section>
            <hr>
        </main>
        <footer class="lkj">
            
              Copyright &copy; SejalFitness.com | All rights reserved
        </footer>
    </div>
</body>

</html>

------------CSS Code---------------------
/* @import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap'); */

@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

* {
    margin: 0;
    padding: 0;

}

.container {
    max-width: 80vw;
    font-family: 'Oswald', sans-serif;
    background-color: #080808;
}

.flex i {
    width: 30%;
    height: 20%;
}

.navbar {
    display: flex;
    height: 67px;

}

.navbar li {
    list-style: none;
    margin: 0 12px;
    color: cornsilk;
}

.topleft {
    width: 50%;

}

.topright {
    width: 50%;


}

.section1 {
    max-height: 550px;
    background-color:#080808;
    color: rgb(255, 255, 255);
}

.section1 h1 {
    font-size: 2rem;
    color: aquamarine;
    font-family: 'Times New Roman', Times, serif;
}

.logo {
    font-size: 1.3rem;
    text-align: middle;

}

.slogan {
    text-align: center;
    padding: 1rem;
    height: 1%;
    font-family: 'Times New Roman', Times, serif;
}

.section2 {
    padding-left: 63px;
    padding-right: 63px;
    background-color: rgb(39, 0, 0);
    color: white;
}

.section2 p {
    padding: 0 8pw;
    text-align: center;
}

.section2 h1 {
    font-size: 2.5rem;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.box {
    padding: 8px 0;
    margin: 12px 22px;
    min-width: 20vw;
    border: 2px solid rgba(1, 1, 5, 0.768);
    border-radius: 8px;
    text-align: center;
    background-color: beige;
    color: #080808;
}

.box h2 {
    font-size: 2rem;
    padding: 15px 0;
}

.highlighted {
    font-size: 1.2rem;
    font-weight: bolder;

}

.box ul {
    list-style-type: none;
}

.box ul li {
    margin: 12px 2px;
}

.plantable {
    display: flex;
    justify-content: center;
    align-items: center;
}

.blcolor {
    background-color: #080808;
}

.section3 table {
    width: 100%;
    margin-bottom: 140px;
    margin-top: 20px;
    border-collapse: collapse;
    background-color: #0099ff;
}

.section3 table th {
    width: 23vw;
    border-bottom: 2px solid black;
    padding: 15px 0;
}

.section3 table td {
    border-bottom: 2px solid black;

}

.section3 table tr {
    border-bottom: 2px solid black;

}

.section3 h1 {
    height: fit-content;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 2.5rem;
    color: black;

}

.section3 {
    padding-left: 63px;
    padding-right: 63px;
    background-color: orangered;
    color: black;
}

.section2 h2 {
    color: goldenrod;
}




/* footer{
    padding: 23px;
    text-align: center;
} */
.footer right {
    text-align: right;
}

.footer {
    background-color: black;
    color: azure;
    width: 100%;
    text-align: left;
    font-family: sans-serif;
    font-weight: bold;
    font-size: 16px;
    padding: 10px;
    margin-top: 50px;
}

.footer .footer-left,
.footer .footer-center,
.footer .footer-right {
    display: inline-block;
    vertical-align: top;
}


/* footer left*/

.footer .footer-left {
    width: 33%;
    padding-right: 15px;
}
.lkj{
    color: white;
    text-align: center;
}
.footer .about {
    line-height: 20px;
    color: #ffffff;
    font-size: 13px;
    font-weight: normal;
    margin: 0;
    text-align: center;
}

.footer .about span {
    display: block;
    color: #ffffff;
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 20px;
    text-align: center;
}

.footer .icons {
    margin-top: 25px;
}

.footer .icons a {
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #33383b;
    border-radius: 2px;
    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;
    margin-right: 3px;
    margin-bottom: 5px;
}


/* footer center*/

.footer .footer-center {
    width: 30%;
}

.footer .footer-center i {
    background-color: #33383b;
    color: #ffffff;
    font-size: 25px;
    width: 38px;
    height: 38px;
    border-radius: 50%;
    text-align: center;
    line-height: 42px;
    margin: 10px 15px;
    vertical-align: middle;
}

.footer .footer-center i.fa-envelope {
    font-size: 17px;
    line-height: 38px;
}

.footer .footer-center p {
    display: inline-block;
    color: #ffffff;
    vertical-align: middle;
    margin: 0;
}

.footer .footer-center p span {
    display: block;
    font-weight: normal;
    font-size: 14px;
    line-height: 2;
}

.footer .footer-center p a {
    color: #0099ff;
    text-decoration: none;
}


/* footer right*/

.footer .footer-right {
    /* width: 35%; */
    width: 10%;
    text-align: middle;
}

.footer h2 {
    color: #ffffff;
    font-size: 36px;
    font-weight: normal;
    margin: 0;
}

.footer h2 span {
    color: #0099ff;
}

.footer .menu {
    color: #ffffff;
    margin: 20px 0 12px;
    padding: 0;
    /* text-align: right; */
}

.footer .menu a {
    display: inline-block;
    line-height: 1.8;
    text-decoration: none;
    color: inherit;
}

.footer .menu a:hover {
    color: #0099ff;
}

.footer .name {
    color: #0099ff;
    font-size: 14px;
    font-weight: normal;
    margin: 0;
}

@media (max-width: 767px) {
    .footer {
        font-size: 14px;
    }

    .footer .footer-left,
    .footer .footer-center,
    .footer .footer-right {
        display: block;
        width: 100%;
        margin-bottom: 40px;
        text-align: center;
    }

    .footer .footer-center i {
        margin-left: 0;
    }
}
.min-h-screen {
    min-height: 100vh;
}

.bg-red {
    background-color: red;
}

.mx-auto {
    margin-left: auto;
    margin-right: auto;
}

.flex {
    display: flex;
}

.items-center {
    align-items: center;
}

.justify-between {
    justify-content: space-between;
}

.justify-center {
    justify-content: center;
}

.flex-col {
    flex-direction: column;
}

.font-bold {
    font-weight: bolder;
}

.my-1 {
    margin-top: 13px;
    margin-bottom: 13px;
    @import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');
}

.my-2 {
    margin-top: 26px;
    margin-bottom: 26px;
}

.px-2 {
    padding-left: 13px;
    padding-right: 13px;
}

.text-blue {
    color: rgb(255, 251, 18);

}

.btn {
    padding: 7px 12px;
    border: 2px solid black;
    border-radius: 6px;
    cursor: pointer;
    color: rgb(2, 2, 2);
    background-color: yellow;
}

.overflow-x-hidden {
    overflow-x: hidden;
}

.text-center {
    text-align: center;
}
