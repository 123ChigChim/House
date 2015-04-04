# House
creating a house app
//the changes has been made in the header.php file

<div id='header'>
        <header class="container col-sm-12 col-md-12 col-lg-12 navbar navbar-fixed-top navbar-default">
            <div class="row">
                <img src="image.jpg" alt="House Logo" id="logo" class="img-circle img-responsive col-md-1 col-lg-1 col-sm-2 col-xs-2"/>
                <h1 class="h1 col-md-6 col-lg-5 col-sm-8 col-xs-9"><strong>Houses In Malawi To Let</strong></h1>
                <button class="btn navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class='glyphicon glyphicon-chevron-down'></span>MENU
                </button>
               <!-- <nav>
                    <div id="nav" class="navbar-collapse collapse">
                        <ul class="nav navbar-nav navbar-right">
                            <li><a href="index.php">Home</a></li>
                            <li><a href="html5_semantic_elements.asp">Northern Region</a></li>
                            <li><a href="html5_geolocation.asp">Central Region</a></li>
                            <li><a href="html5_canvas.asp">Southern Region</a></li>
                            <li><a href="singup.php">Sing Up</a></li>
                            <li><a href="login.php">Login</a></li>
                        </ul>
                    </div>
                </nav>-->
				<nav class="navbar navbar-inverse">
  
    <div class="navbar-header">
      <a class="navbar-brand" href="#">House</a>
    </div>
    <div>
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Northen Region <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Chitipa</a></li>
            <li><a href="#">Karonga</a></li>
            <li><a href="#">Mzimba</a></li>
			<li><a href="#">Nkhata-Bay</a></li>
            <li><a href="#">Rumphi</a></li>
            <li><a href="#">Likoma Island</a></li>
          </ul>
        </li>
		<li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Central Region <span class="caret"></span></a>
		<ul class="dropdown-menu">
            <li><a href="#">Lilongwe</a></li>
            <li><a href="#">Salima</a></li>
            <li><a href="#">Ntcheu</a></li>
			<li><a href="#">Ntchisi</a></li>
            <li><a href="#">Dedza</a></li>
            <li><a href="#">Mchinji</a></li>
			<li><a href="#">Dowa</a></li>
            <li><a href="#">Kasungu</a></li>
			<li><a href="#">Nkhotakota</a></li>
        
          </ul>
        </li>
		<li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Southern Region <span class="caret"></span></a>
		<ul class="dropdown-menu">
            <li><a href="#">Blantyre</a></li>
            <li><a href="#">Balaka</a></li>
            <li><a href="#">Chikwawa</a></li>
			<li><a href="#">Chiradzulu</a></li>
            <li><a href="#">Machinga</a></li>
            <li><a href="#">Mangochi</a></li>
			<li><a href="#">Mulanje</a></li>
            <li><a href="#">Mwanza</a></li>
			<li><a href="#">Neno</a></li>
            <li><a href="#">Nsanje</a></li>
            <li><a href="#">Phalombe</a></li>
			<li><a href="#">Thyolo</a></li>
            <li><a href="#">Zomba</a></li>
          </ul>        
        </li>
		<li><a href="singup.php">Sign Up</a></li>
        <li><a href="login.php">Login</a></li>
      </ul>
    </div>
  <?php
echo "The time is " . date("h:i:sa");
?>
</nav>
            </div>
            <form method='post' action='search.php' class="form-horizontal row" id="search">
                <input class='item' type='text' name="search">
                <input class='item btn btn-success' type='submit' name='search' value='search'>
            </form>
        </header>
</div>
