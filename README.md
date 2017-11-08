# BullShipp2
# Title Page
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? Title Page
        </title> 
        <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
        <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script> 
    </head>
        <body>
            <div data-role="page">
                <div data-role="header">
                    <script type="text/javascript" src="cordova.js"></script>
                    <h1>Where You App?</h1>
                </div>
                <div data-role="main" class="ui-content">
                    <label for="TitlePage">Where My Friends App?</label><br /><br />
    
                    <button class="btn btn-success" onclick=" window.location.href='./LogInPage.html'"id="btnLogIn">Login</button><br /><br />
         
                    <button class="btn btn-success" onclick="window.location.href='./SignInPage.html'"id="btnSignIn">Sign Up</button>
                    <br /><br />
    
                    <button id="btnExit">Exit</button>
                    <div id="result"></div>
                </div>
                <div data-role="footer">
                    <p>Made by Sam and He is Great</p>
                </div>
            </div>
        </body>
    <body>
        <script type="text/javascript" src="cordova.js"></script>
    </body>
</html>


# Sign In
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? Sign In</title> 
            <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
            <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js">
            </script> 
    </head>
        <body>
            <div data-role="page">
                <div data-role="header">
                    <h1>Where You App?</h1>
                </div>
                <div data-role="main" class="ui-content">
                    <label>Where My Friends App?</label><br />
                    
                    <label for="SUUsername">Username:</label>
                    <input id="SUUsername" type="text" /><br />
                    
                    <label for="SUEmail">Email:</label>
                    <input id="SUEmail" type="email" /><br />
                    
                    <label for="SUEmailConfirm">Email Confirm:</label>
                    <input id="SUEmailConfirm" type="email" /><br />
                    
                    <label for="SUPassword">Password:</label>
                    <input id="SUPassword" type="password" /><br />
                    
                    <label for="SUPasswordConfirm">Password Confirmation:</label>
                    <input id="SUPasswordConfirm" type="password" /><br />

                    <br /><br /><button class="btn btn-success" onclick=" window.location.href='./HomePage.html'"id="btnSignInConfirm">Sign Up</button><br />
    
                    <br /><br /><button class="btn btn-success" onclick="window.location.href='./index.html'"id="btnBack">Back</button>
                    <div id="result"></div>
                </div>
                <div data-role="footer">
                    <p>Made by Sam and He is Great</p>
                </div>
            </div>
        </body>
    <body>
        <script type="text/javascript" src="cordova.js"></script>
    </body>
</html>


#Log In
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? Log In</title> 
        <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
        <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script> 
    </head>
    <body>
        <div data-role="page">
            <div data-role="header">
                <h1>Where You App?</h1>
            </div>
            <div data-role="main" class="ui-content">
                <label for="WUA">Where My Friends App?<br /></label>
                
                <label for="LIUsername">Username:</label>
                
                <input id="LIUsername" type="text" /><br />
                
                <label for="LIPassword" >Password:</label>
                
                <input id="LIPassword" type="password" /><br />
    
                <button class="btn btn-success" onclick=" window.location.href='./HomePage.html'"id="btnLoginConfirm">Login</button><br />
    
                <button class="btn btn-success" onclick="window.location.href='./index.html'"id="btnBack">Back</button>
                <div id="result"></div>
            </div>
            <div data-role="footer">
                <p>Made by Sam and He is Great</p>
            </div>
        </div>
    </body>
    <body>
        <script type="text/javascript" src="cordova.js"></script>
    </body>
</html>


#Home Page
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? HomePage</title> 
        <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
        <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
    </head>
    <body>
        <div data-role="page">
            <div data-role="header">
                <h1>Where You App?</h1>
            </div>
            <div data-role="main" class="ui-content">
                <label for="WUA">Where My Friends App?</label><br /><br />
    
                <button class="btn btn-success" onclick=" window.location.href='./ContactList.html'"id="btnFind">Find Friend</button><br /><br />
    
                <button class="btn btn-success" onclick="window.location.href='./index.html'"id="btnLogOut">Log Out</button>
                <div id="result"></div>
            </div>
            <div data-role="footer">
                <p>Made by Sam and He is Great</p>
            </div>
        </div>
    </body>
    <body>
        <script type="text/javascript" src="cordova.js"></script>
    </body>
</html>


#Contact List
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? ContactList</title> 
        <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
        <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>

    </head>
    <body>
        <div data-role="page">
            <div data-role="header">
                <h1>Where You App?</h1>
            </div>
            <div data-role="main" class="ui-content">
                <label for="WUA">Where My Friends App?</label><br>
                <select size="1" id="Contacts" name="Contacts">
                    <option type="radio" name="Contact" id="ContactA" value="ContactA"/>Contact A<br>
                    <option type="radio" name="Contact" id="ContactB" value="ContactB"/>Contact B<br>
                    <option type="radio" name="Contact" id="ContactC" value="ContactC"/>Contact C<br>
                </select>
                <script type="text/javascript" src="./Contact.js"></script>

                <input type="submit" value="Select Contact" class="btn btn-success" onclick=" window.location.href='./MapPage.html'"id="btnFind"/>
                <button  class="btn btn-success" onclick=" window.location.href='./MapPage.html'"id="btnFind">Find</button><br />
    
                <button class="btn btn-success" onclick="window.location.href='./HomePage.html'"id="btnLogOut">Close</button>
                        <div id="result"></div>
                
                </div>
            <div data-role="footer">
                <p>Made by Sam and He is Great</p>
            </div>
        </div>
    </body>
    <body>
    </body>
</html>



#Map Page
<!DOCTYPE html>
<html>
    <head>
        <title>Where You App? MapPage</title> 
        <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script> 
        <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>

          

    </head>
    <body>
        <div data-role="page">
            <div data-role="header">
                <h1>Where You App?</h1>

           <div id="map" style="width:400px;height:400px"></div>
                                <script>
        function MainMap(){
            var mapOptions = {
                center: new google.maps.Latlng(51.5, -0.12),
                zoom: 10
                mapTypeId: google.maps.MapTypeId.HYBRID
            }
            var map = new google.maps.Map(document.getElementById("map"), mapOptions)
        }
        </script>
        <script src="https://maps.googleapis.com/maps/api/js?callback=MainMap"></script>
                
            <div data-role="footer">
                <p>Made by Sam and He is Great</p>
            </div>
        </div>
        </div>
    </body>
    <body>
        <script type="text/javascript" src="cordova.js"></script>

    </body>
</html>

#Contact.js
<!DOCTYPE Java>
<html>
public class IfElseIf {
	public static void main(String[] args) {

		int round = 6;

		if (round > 12) {

			System.out.println("The match is over!");

		} else if (round > 0) {

			System.out.println("The match is underway!");

		}	else {

			System.out.println("The boxing match hasn't started yet.");

		}	
	}
}
</html>
