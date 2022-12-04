# electricity-website
this is the html and css code that I have done for making an electricity website.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="kl.jpg">
    <title>INDIAN ELECTRICITY BOARD</title>
    <link rel="stylesheet" href="csselectric.css">
</head>

<body>
    <!-- <div class="sam"> <a href="26nov.html"><img src="WhatsApp Image 2022-11-26 at 16.53.32.jpg" alt=""></a></div> -->
    <section class="header">
        
        <nav>
            
            <div class="sam" ><center>INDIAN ELECTRICITY BOARD</center></div>
            
            <div class="demon">
                <ul>
                    <li><a href="">Home</a></li>
                    <li><a href="">About</a></li>
                    <li><a href="">Service</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>
            </div>
        </nav>
    <div class="front-page">
        <h1 style="color: #fff;"><b>WELCOME</b></h1>
        <p style="font-size: 24px;" style="color:#fff">The creation of Indian Power Corporation Ltd. (IPCL) on January 14, 1968 is the result of power sector reforms and restructuring in India which is the focal point of the Power Sector, responsible for planning and managing the sector through its transmission, distribution and supply of electricity.

            IPCL will be professionally managed utility supplying reliable and cost efficient electricity to every citizen of the country through highly motivated employees and state of art technologies, providing an economic return to our owners and maintaining leadership in the country.
            
        </p>
        
        <a href="" class="intro"><b> EXLPORE</b></a>
    </div>
    </section>
    <div class="op">
    <section class="payment">

        <h1 style="color: #fff"><b>LOGIN </b></h1>
        
        <div class="row">
            <div class="payment-col">
                
                <form method="post">
                    <div class="txt_field">
                        <input type="text" required>
                        <label>Username</label>
                    </div>
                    <div class="txt_field">
                        <input type="password" required>
                        <label>Password</label>
                    </div>
                    <div class="pass">Forget Password?</div>
                    <input type="button" value="Login">
                    <div class="signup_link">Not registered?<a href="#">Signup</a>
                    </div>
                </form>

            </div>
        </div>

    </section>
    <section>
        
        <header>
    
            <div class="container">
                
                <div class="left">
                    <h3>BILLING ADDRESS</h3>
                    <form>
                        Full name
                        <input type="text" name="" placeholder="Enter name">
                        Email
                        <input type="text" name="" placeholder="Enter email">
                        Address 
                        <input type="text" name="" placeholder="Enter address">
                        City
                        <input type="text" name="" placeholder="Enter city">
                        <div id="zip">
                            <label>
                                State
                                <select name="" id="">
                                    <option value="">Choose State</option>
                                    <option value="">Rajasthan</option>
                                    <option value="">Hariyana</option>
                                    <option value="">Uttar Pradesh</option>
                                    <option value="">Madhya Pradesh</option>
                                    <option value="">Punjab</option>
                                    <option value="">Andhra Pradesh</option>
                                </select>
                            </label>
                            <label for="">
                                Zip code
                                <input type="number" name="" placeholder="Zip code">
                            </label>
                        </div>
                    </form>
                </div>
                <div class="right">
                    <h3>PAYMENT</h3>
                    <form>
                        Accepted Card <br>
                        <img src="io.jpg" width="150">
                        <!-- <img src="" width="100"> -->
                        <br><br>
                    
                        Credit card number 
                        <input type="text" name="" placeholder="Enter card number">
                        
                        Exp month
                        <input type="text" name="" placeholder="Enter Month">
                        <div id="zip">
                            <label>
                                State
                                <select name="" id="">
                                    <option value="">Choose Year..</option>
                                    <option value="">2022</option>
                                    <option value="">2023</option>
                                    <option value="">2024</option>
                                    <option value="">2025</option>
                                </select>
                            </label>
                            <label for="">
                                CVV
                                <input type="number" name="" placeholder="CVV">
                            </label>
                            
                        </div>
                        
                    </form>
                    <input type="sumbit" name="" value="Proceed to Checkout">
                </div>

            </div>

        </header>
    </section>
    <section>
        <ul id="accordion">
            <li>
                <h1>    FAQ</h1>
                <label for="first">How to register online? <span>&#x3e;</span></label>
                    <input type="radio" name="accordion" id="first" checked>
                    <div class="content">
                        <p style="font-size: 24px;">To register online visit our website www.uppclonline.com. For registeration you should know your Account ID printed in the Bill provided by us and the Bill number as printed in the Bill. Click on the Register Button on the home page and enter your Account ID and Bill ID. You will be displayed with your details.
                            Validate your details and enter your email address, Mobile number, password, secret question and secret answer. On submitting you would be send a confirmation mail to your mail id. Click on the link in the mail and login to activate your account. On successful activation your online registration would complete.</p>
                    </div>
    
            </li>
            <li>
                <label for="second">Where I can pay my bills? <span>&#x3e;</span></label>
                    <input type="radio" name="accordion" id="second" >
                    <div class="content">
                        <p style="font-size: 24px;">You can pay your Utility Bills from following points
                            - Web Self Service at www.uppclonline.com
                            - Collection Centers
                            - Customer Care Centers
                            - KIOSK installed at various Customer Care Centers</p>
                    </div>
    
            </li>
            <li>
                <label for="third">I have forgotten my password.How to retrieve it? <span>&#x3e;</span></label>
                    <input type="radio" name="accordion" id="third" >
                    <div class="content">
                        <p style="font-size: 24px;">If you have forgotten your Online Password then visit our website www.uppclonline.com. Click on the Forgot Password button on the home page. Enter your Account ID printed in the Bill provided by us. Enter the security answer as entered during registration.
                            If your Email Address has been confirmed with us the regenerated password would be send to your email address. If your email address has not been confirmed with us you would be asked to confirm the email address or change the same in the next screen, submitting on this screen would send an email with the regenerated password.</p>
                    </div>
            </li>
            <li>
                <label for="forth">What if my ID is already registered? <span>&#x3e;</span></label>
                    <input type="radio" name="accordion" id="forth" >
                    <div class="content">
                        <p style="font-size: 24px;">During registration if you see a message that my ID is already registered then call our Customer Care Center and provide your Account ID. Validate your details with our agent and successful verification your account would be reset and you can register yourself online again.</p>
                    </div>
            </li>
            <li>
                <label for="fifth">What if i have forgotten my password as well as my secret answer? <span>&#x3e;</span></label>
                    <input type="radio" name="accordion" id="fifth" >
                    <div class="content">
                        <p style="font-size: 24px;">If you have forgotten your Password as well as my Secret Answer then call our Customer Care Center and provide your Account ID. Validate your details with our agent and successful verification your account would be reset and you can register yourself online again.
                        </p>
                    </div>
            </li>
        </ul>
        
   
    
        <div class="coe">
        <div class="row78">
            <div class="coe-col">
                <h1>WAYS TO CONSERVE ELECTRICITY</h1>
                <p style="font-size:22px; font-weight:400;"> 1.One of the best energy-saving devices is the light switch. Turn off lights when not required.
                    <br><br>
                    2. As for as possible use task lighting, which focuses light where it's needed. A reading lamp, for example,
                    lights only reading material rather than the whole room.
                    <br><br>
                    3.Keep doors to air-conditioned rooms closed as often as possible.
                    <br><br>
                    4.Dirty tube lights and bulbs reflect less light and can absorb 50 percent of the light; dust your tube lights
                    and lamps regularly.
                    <br><br>
                    5.A full refrigerator is a fine thing, but be sure to allow adequate air circulation inside.
                    <br><br>
                    6.Ninety percent of the energy consumed by an ordinary bulb (incandescent lamp) is given off as heat
                    rather than visible light.
                    <br><br>
                    7.If room air conditioner is older and needs repair, it's likely to be very inefficient. It may work out cheaper
                    on life cycle costing to buy a new energy-efficient air conditioner.
                    <br><br>
                    8.To help reduce heat loss, always insulate hot water pipes, especially where they run through unheated
                    areas. Never insulate plastic pipes.
                    <br><br>
                    9.If your computer must be left on, turn off the monitor; this device alone uses more than half the system's
                    energy.
                    <br><br>
                    10.Don't overfill the kettle for just one drink. Heat only the amount of water you need.
                    <br><br>
                    11.Using ceiling or room fans allows you to set the thermostat higher because the air movement will cool the
                    room.
                    <br><br>
                    12.Battery chargers, such as those for laptops, cell phones and digital cameras, draw power whenever they
                    are plugged in and are very inefficient. Pull the plug and save.
                    <br><br>
                    13.Think about what you need before opening refrigerator door. You'll reduce the amount of time the door
                    remains open.
                    <br><br>
                    14.When buying a new electric kettle, choose one that has an automatic shut-off button and a heat-resistant
                    handle.
                    <br><br> 
                    14.When buying a new electric kettle, choose one that has an automatic shut-off button and a heat-resistant
                    handle.
                    <br><br>
                    15. A good air conditioner will cool and dehumidify a room in about 30 minutes, so use a timer and leave the
                    unit off for some time.
                    <br><br>
                    16.Make sure that refrigerator's rubber door seals are clean and tight. They should hold a slip of paper
                    snugly. If paper slips out easily, replace the door seals.
                    <br><br>
                    17.Turn off your home office equipment when not in use. A computer that runs 24 hours a day, for instance,
                    uses - more power than an energy-efficient refrigerator.
                    <br><br>
                    18.Screen savers save computer screens, not energy. Start-ups and shutdowns do not use any extra energy,
                    nor are they hard on your computer components. In fact, shutting computers down when you are finished
                    using them actually reduces system wear - and saves energy.
                    <br><br>
                    19.Remember, microwaves cook food from the outside edge toward the centre of the dish, so if you're cooking more than one item, place larger and thicker items on the outside.
                    <br><br>
                    20.Allow hot and warm foods to cool and cover them well before putting them in refrigerator. Refrigerator will use less energy and condensation will reduced.
                    <br><br>

                </p>
            </div>
            
            <div class="coe-col23">
                <h1>STATE WISE CONSUMPTION (kWh)</h1>
                <div class="grid-container" >
                    
                    <div class="item1"><h3>State/UTs</h3></div>
                    <div class="item43"><h3>Per Capita Consumption(kWh)</h3></div>
                    <div class="item2">Chandigarh</div>
                    <div class="item44">1128</div>
                    <div class="item3">Delhi</div>
                    <div class="item45">1574</div>
                    <div class="item4">Haryana</div>
                    <div class="item46">1975</div>
                    <div class="item5">Himachal Pradesh</div>
                    <div class="item47">1340</div>
                    <div class="item6">Jammu & Kashmir</div>
                    <div class="item48">1282</div>
                    <div class="item7">Punjab</div>
                    <div class="item49">2028</div>	
                    <div class="item8">Rajasthan</div>
                    <div class="item50">1166</div>
                    <div class="item9">Uttar Pradesh</div>
                    <div class="item51">585</div>
                    <div class="item10">Uttarakhand</div>	
                    <div class="item52">1454</div>
                    <div class="item11">Northern Region</div>
                    <div class="item53">1003</div>
                    <div class="item12">Chhattisgarh</div>
                    <div class="item54">2016</div>
                    <div class="item13">Gujarat</div>
                    <div class="item55">2279</div>
                    <div class="item14">Madhya Pradesh</div>
                    <div class="item56">989</div>
                    <div class="item15">Maharashtra</div>
                    <div class="item57">1307</div>
                    <div class="item16">Daman & Diu</div>
                    <div class="item58">7956</div>
                    <div class="item17">Dadra & Nagar Haveli</div>
                    <div class="item59">13783</div>
                    <div class="item18">Goa</div>
                    <div class="item60">2466</div>
                    <div class="item19">Western Region</div>
                    <div class="item61">1533</div>
                    <div class="item20">Andhra Pradesh</div>
                    <div class="item62">1319</div>
                    <div class="item21">Telangana</div>
                    <div class="item63">1551</div>
                    <div class="item22">Karnataka</div>
                    <div class="item64">1367</div>
                    <div class="item23">Kerala</div>
                    <div class="item65">763</div>
                    <div class="item24">Tamil Nadu</div>
                    <div class="item66">1847</div>	
                    <div class="item25">Puducherry</div>
                    <div class="item67">1784</div>	
                    <div class="item26">Lakshadweep</div>
                    <div class="item68">633</div>
                    <div class="item27">Southern Region</div>
                    <div class="item69">1432</div>
                    <div class="item28">Bihar</div>	
                    <div class="item70">272</div>
                    <div class="item29">Jharkhand</div>
                    <div class="item71">915</div>	
                    <div class="item30">Odisha</div>
                    <div class="item72">1622</div>	
                    <div class="item31">West Bengal</div>	
                    <div class="item73">665</div>
                    <div class="item32">Sikkim	</div>
                    <div class="item74">806</div>
                    <div class="item33">Andaman- Nicobar</div>
                    <div class="item75">370</div>	
                    <div class="item34">Eastern Region</div>
                    <div class="item76">695</div>	
                    <div class="item35">Arunachal Pradesh</div>
                    <div class="item77">648</div>	
                    <div class="item36">Assam</div>
                    <div class="item78">339</div>	
                    <div class="item37">Manipur</div>
                    <div class="item79">326</div>	
                    <div class="item38">Meghalaya</div>
                    <div class="item80">832</div>	
                    <div class="item39">Mizoram</div>
                    <div class="item81">523</div>	
                    <div class="item40">Nagaland</div>
                    <div class="item82">345</div>	
                    <div class="item41">Tripura</div>
                    <div class="item83">470</div>	
                    <div class="item42">North-Eastern Region</div>
                    <div class="item84">392</div>
                </div>
            </div>
        </div>
        </div>
</section>
    <section>
        <div class="about-section">
            <h1 style="color:#fff;font-size:48px"><b>ABOUT US</b></h1>
            <p style="font-size: 24px;">The Ministry of Power started functioning independently with effect from 2nd July, 1992. Earlier it was known as the Ministry of Energy sources. Electricity is a concurrent subject at Entry 38 in List III of the seventh Schedule of the Constitution of India. The Ministry of Power is primarily responsible for the development of electrical energy in the country. The Ministry is concerned with perspective planning, policy formulation, processing of projects for investment decision, monitoring of the implementation of power projects, training and manpower development and the administration and enactment of legislation in regard to thermal, hydro power generation, transmission and distribution.</p>
            
          </div>
          
          <h1 style="text-align:center;color:#fff;"><b>Ministry of Power</b></h1>
          <div class="row1">
            <div class="column1">
              <div class="card">
                <img src="p5.jpg" alt="Raj Kumar Singh" style="width:100%">
                <div class="container1">
                  <h2><b>Raj Kumar Singh</b></h2>
                  <p class="title1"><b>Union Cabinet Minister</b></p>
                  <p style="font-size: 18px;">The Ministry of Power is an Indian government ministry. The current Union Cabinet Minister is Raj Kumar Singh. The ministry is charged with overseeing electricity production and infrastructure development, including generation, transmission, and delivery, as well as maintenance projects.</p>
                  <p>rajkumarsingh@gmail.com
                    084271 00383
                  </p>
                  <p><button class="button1">Contact</button></p>
                </div>
              </div>
            </div>
          
            <div class="column1">
              <div class="card">
                <img src="1.jpg" alt="Shri RK Singh" style="width:100%">
                <div class="container1">
                  <h2><b>Shri RK Singh</b></h2>
                  <p class="title1"><b>Cabinet Minister</b></p>
                  <p style="font-size: 18px;">Raj Kumar Singh (born 20 December 1952) is a former Indian bureaucrat and a current Union Cabinet Minister in the Government of India. He is a Member of the Indian Parliament for Arrah, Bihar, since May 2014. Singh is a 1975 batch Bihar cadre[2] Indian Administrative Service officer and former Home Secretary of India</p>
                  <p>rksingh@gmail.com</p>
                  <p><button class="button1">Contact</button></p>
                </div>
              </div>
            </div>
          
            <div class="column1">
              <div class="card">
                <img src="1234.jpg" alt="Shri Krishan Pal" style="width:100%" height="50%">
                <div class="container1">
                  <h2><b>Shri Krishan Pal</b></h2>
                  <p class="title1"><b>Minister of state for power</b></p>
                  <p style="font-size: 18px;">Krishan Pal Gurjar (born 4 February 1957) is an Indian politician and is the present Minister of State of Power and Heavy Industries. As a Member of Parliament in the Lok Sabha, he represents the Faridabad constituency in the state of Haryana. </p>
                  <p>krishanpal@gmail.com</p>
                  <p><button class="button1">Contact</button></p>
                </div>
              </div>
            </div>
          </div>
       </section> 
       </div>
       <!-- footer
    <section class="footer">
        <h4>About us</h4>
        <p>“Travel is the only thing you buy that makes you richer”.</p>
        <div class="icons">
            <i class="fa fa-facebook"></i>
            <i class="fa fa-twitter"></i>
            <i class="fa fa-instagram"></i>
            <i class="fa fa-linkedin"></i>        
         </div>
         <p>Made With <i class="fa fa-heart-o"></i>by A3</p>
    </section>
           -->
        
</body>
</html>
css-*{
    margin :0;
    padding: 0;
    

}
.header{
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(yt.jpg);
    background-position: center;
    background-size: cover;
    position: relative;
    
}
nav{
    display: flex;
    padding: 2% 6%;
    justify-content: space-between;
    align-items: center;
    height: 160px;
}
.sam {
    font-size: 300%;
    color:#fff;
    font-family:Arial, Helvetica, sans-serif;
    font-weight: 700;
    font-size: 72px;
}
.sam center{
       font-family: Arial, Helvetica, sans-serif;
}
.demon ul li{
    display: inline-block;
    padding: 8px 12px;
    text-align: center;
    font-weight: 500;
    font-size: 26px;
}
.demon ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 23px;
}
.demon ul li::after{
    content: "";
    width: 0%;
    height: 2px;
    background: #f44336;
    display: block;
    margin: auto;
    transition: 0.5s;
}
.demon ul li:hover::after{
    width: 100%;

}
.front-page{
    width: 90%;
    color: #fff;
    position: absolute;
    top:56%;
    left:50%;
    transform: translate(-50%,-50%);
    text-align: center;
}
.front-page h1{
    font-size: 38px;
}
.front-page p{
    margin: 50px 0 40px;
    font-size:14px;
    color: #fff;
}
.intro{
    display: inline-block;
    text-decoration:crimson;
    color: #fff;
    border: 1px solid white;
    padding: 12px 34px;
    font-size: 16px;
    background:transparent;
    position: relative;
    cursor: pointer;
}
.intro:hover{
    border: 1px solid  #d8483e;
    background-color: #d8483e;
    transition: 1s;
}

/* page2 */
.payment{
    width: 100%;
    margin: auto;
    background-image: url("98.jpg");
    background-position: center;
    background-size:contain;
    position: relative; 
    text-align: center;
    padding-top: 100px;
}
.payment h1{
    font-size: 54px;
}
.payment p{
    color: rgb(97, 20, 20);
    font-size:14px;
    line-height: 22px;
    padding: 10px;
}
.row {
    margin-top:5%;
    margin-left: 45%;
    display: flex;
    justify-content: space-between;
    /* transform: translate(50%,50%); */
    top: 50%;
    left: 50%;
}
.payment-col{
    
    background:#c1f5fd;
    border-radius: 10px;
    margin-bottom: 25%;
    padding: 20px 12px;
    box-sizing:content-box;
    top: 10%;
    left: 50%;
    transform: translate(-40%,-10%);
    width: 800px;
    /*background: #fff;*/
    border-radius: 10px;
}
.payment-col h3{
    text-align: center;
    padding: 0 0 20px 0;
    border-bottom: 1px solid sliver;

}
.payment-col form{
    padding: 0 40px;
    box-sizing: border-box;
}
form .txt_field{
    position: relative;
    border-bottom:2px solid rgb(0, 136, 255);
    margin:30px 0;
}
.txt_field input{
    width: 100%;
    padding: 0 5px;
    height: 40px;
    font-size: 16px;
    border: none;
    background: none;
    outline:none;
}
.txt_field label{
    position: absolute;
    top: 50%;
    left: 5px;
    color: black;
    transform: translateY(-50%);
    font-size: 16px;
    pointer-events: none;
    transition: 0.5s;
}
.txt_field span::before{
    content: '';
    position: absolute;
    top: 40px;
    left:0;
    width:0%;
    height:2px;
    background: #2691d9;
    transition: 0.5s;

}
.txt_field input:focus ~ label,.txt_field input:valid ~ label{
    top:-5px;
    color: #2691d9;


}
.txt_field input:focus ~ span::before,.txt_field input:valid ~ span::before{
    width: 100%;
}
.pass{
    margin: -5px 0 20px 5px;
    color: #0a0808;
    cursor: pointer;
}
.pass:hover{
    text-decoration: underline;
}
input[type="button"]{
    width: 100%;
    height: 50px;
    border:1px solid;
    background: #2691d9;
    border-radius: 25px;
    font-size: 18px;
    color:#e9f4fb;
    font-weight: 700;
    cursor: pointer;
    outline:none;
}
input[type="button"]:hover{
    border-color: #2691d9;
    transition: .5s;
}
.signup_link{
    margin: 30px 0;
    text-align: center;
    font-size: 16px;
    color: #666666;
}
.signup_link a{
    color: #2691d9;
    text-decoration:none;
}
.signup_link a:hover{
    text-decoration: underline;
}
/* page 3 */
header{
    width: 100vw;
    min-height: 100vh;
     background-image: url("87.jpg");
    background-position: center;
    background-size: cover; 
    font-size: 1.2rem;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container{
    background: white;
    max-width: 900px;
    min-width: 300px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding:0.5rem 1.5rem;
}

form{
    padding: 1rem;
}
h3{
    margin-top: 1rem;
    color: #2f2bb5;
}
form input[type="text"]{
    width: 100%;
    padding: 0.5rem 0.7rem;
    margin:0.5rem 0;
    outline: none;
}
#zip{
    display: flex;
    margin-top: 0.5rem;
}
#zip select{
    padding: 0.5rem 0.7rem;
}
#zip input[type="number"]{
    padding: 0.5rem 0.7rem;
    margin-left: 5px;
}
input[type="submit"]{
    width:100%;
    padding: 0.7rem 1.5rem;
    background: #fff;
    color: white;
    border: none;
    outline: none;
    margin-top: 2rem;
    cursor: pointer;
}
input[type="sumbit"]:hover{
    background: #0f73d6;
}
*{
    box-sizing: border-box;
    font-family:  -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
main{
    max-width: 800px;
    margin: 5vh auto;
    padding:20px;
}
h1{
    font-size: 2.5em;
    font-weight: 400;
    margin-bottom: 40px;
    color: #707070;

}
h2{
    font-size: 1.1em;
    font-weight: 400;
    color: #5e5d5d;

}
.faq{
    padding:20px 30px;
    border: 1px solid rgba(0 0 0/.1);
    border-radius: 5px;
    color: #979797;
    position: relative;
    line-height: 1.5em;
    margin-top: 15px;
}
.faq .faq_text{
    width: 90%;

}
.btn{
    color: #5e5d5d;
    position: absolute;
    right: 5px;
    top: 35px;
    font-weight: 400;
    font-size: 1.4em;


}
/* hide p tags */
.faq.open h2{
    color: #00848f;

}
.faq p{
    display: none;
}
.faq.open p{
    display:block;

}
.faq.open .btn{
    color:#00848f;
}
/* footer */
footer{
    max-width: 800px;
    width: 100%;
    margin: 0 auto;
    border-top: 1px solid rgba(00 84 80/.2);
    padding-top: 50px;
}
footer h2{
    font-style: normal;
}


body{
    background: skyblue;

}
#accordion{
     background-image: url("87.jpg");
    background-position: center;
    background-size: cover; 
    
    margin: 100px;
    width: 90%;
}
#accordion li{
    list-style: none;
    width:100%;
    margin-bottom: 10px;
    background-color:#fff;
    padding: 10px;
    border-radius: 4px;
}
#accordion li label{
    padding: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 26px;
    font-weight: 500;
    cursor: pointer;
    color: c20000;
}
#accordion li label span{
    transform: rotate(90deg);
    font-size: 22px;
    color: #333;
}
#accordion label+input[type="radio"]{
    display: none;
}
#accordion .content{
    padding: 0 10px;
    line-height: 26px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s;


}
#accordion label+input[type="radio"]:checked +.content{
    max-height: 400px;
    
}
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    background-image: url("OIP.jpg");
    background-position: center;
    background-size:cover;
  }
  
  html {
    box-sizing: border-box;
  }
  
  *, *:before, *:after {
    box-sizing: inherit;
  }
  
  .column1 {
    float: left;
    width: 33.3%;
    background-color: #fff;
    margin-bottom: 16px;
    padding: 0 8px;
  }
  
  .card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    margin: 8px;
  }
  
  .about-section {
    background-image: url("t85YOB.webp");
    background-position: center;
    background-size: cover;
    padding: 50px;
    text-align: center;
    background-color:black;
    color: white;
  }
  .coe{
    width: 80%;
    margin-left: -20px;
    /* background-image: url("R.jpg");
    background-position: center;
    background-size:cover; */
    
    text-align: center;
    margin-top: -15%;
    padding-top: 20px;
    left: 500px;  
}
.coe-col p{
    color:rgb(6, 16, 16);
    font-size: 14px;
    font-weight: 300;
    line-height: 22px;
    padding: 2px;
    width: 550px;
}
.row78{
    margin-top: 25%;
    margin-left: 25%;
    display:flex;
    justify-content:space-around;

}
.coe-col{
    flex-basis: 30%;
    background:#f6fff3;
    border-radius: 10px;
    margin-bottom: 5%;
    padding:10px 12px;
    box-sizing: border-box;
    transition: 0.5s;
    
}

.coe-col h1{
    font-size: 45px;
    font-weight: 600;
    text-align: center;
    font-weight: 600;
    margin: 10px 0;
}
.coe-col:hover{
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
.coe-col p{
    text-align: left;
}
.grid-container {
    display: grid;
    grid-template-columns: 150px auto;
    gap: 2px;
    padding:2px;
}
  
.grid-container > div {
    background-color: rgba(255, 255, 255, 0.8);
    text-align: center;
    padding: 2px 0;
    font-size: 22px;
    font-weight: 400;
}
.coe-col23{
    margin-left: 23%;
    flex-basis: 30%;
    background:#f6fff3;
    border-radius: 10px;
    margin-bottom: 5%;
    padding:10px 12px;
    box-sizing: border-box;
    transition: 0.5s;
    
}
.coe-col23:hover{
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
.coe-col23 h1{
    font-size: 45px;
    font-weight: 600;
    text-align: center;
    font-weight: 600;
    margin: 10px 0;
}
.rt{
    margin-left: -20%;
}
