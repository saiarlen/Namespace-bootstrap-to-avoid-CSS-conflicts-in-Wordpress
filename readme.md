<code>
	<style type="text/css">
		strong {
		color: #467520;
	}
	a {
		text-decoration: none;
		color: #cc0606;
	}
		
	</style>
</code>
<ul>
	<li><a href="https://github.com/twbs/bootstrap">Download</a> the latest bootstrap from their official Github page</li>
	<li><a href="https://nodejs.org/en/download/">Install node</a> Modules in your system</li>
	<li>Now open a terminal and navigate the bootstrap folder as a root</li>
	<li>Run <strong>npm install</strong> to install all local dependencies </li>
	<li><a href="https://www.ruby-lang.org/en/documentation/installation/">Install ruby </a></li>
	<li>install <a href="https://bundler.io/">Bundler</a> with <strong>sudo gem install bundler</strong>
		<ul>
			<li>for Windows users follow the link to <a href="https://jekyllrb.com/docs/installation/windows/">install bundler</a></li>
		</ul>
	</li>
	<li>Now run <strong>bundle install</strong></li>
	<li><p>Now open your bootstrap folder and navigate to scss folder and open <b>bootstrap.scss</b> file with file editor and wrap all <code>@import</code> modules and prefix with your <b>custom class</b></p></li>

</ul>
<code>
	.Custom_class {

		// Configuration

		@import "functions";
		@import "variables";
		@import "mixins";
		@import "utilities";


		// Layout & components

		@import "root";
		@import "reboot";
		@import "type";
		@import "images";
		@import "grid";
		@import "tables";
		@import "forms";
		@import "buttons";
		@import "transitions";
		@import "dropdown";
		@import "button-group";
		@import "nav";
		@import "navbar";
		@import "card";
		@import "breadcrumb";
		@import "pagination";
		@import "badge";
		@import "alert";
		@import "progress";
		@import "list-group";
		@import "close";
		@import "toasts";
		@import "modal";
		@import "tooltip";
		@import "popover";
		@import "carousel";
		@import "spinners";


		// Helpers

		@import "helpers";


		// Utilities

		@import "utilities/api";
	}

</code>

<ul>
	<li>And open your minimized terminal and run <strong>npm run dist</strong></li>
	<li>Boom!!! now check your bootstrap.css file</li>
</ul>

<p><b>Note:</b>  finally open your bootstap file and remove the prefixed class before html and body tags</p>

<br>
<br>
<br>
<br>
<p>Download boorstrsp prefixed with .alms class! if you want you can replace the class with your own class name :)</p>


<h6>Example</h6>
<br>

<code>
	
	<body class = ".alms">
	   <div class= "row">
	     <div class = "col-sm-12"> 
	        <h1> enjoy </h1>
	     </div>
	    </div>    
	</body>
	

</code>

<br>
<br>
<br>
<br>
<br>
<br>
<a href="https://getbootstrap.com/docs/4.4/getting-started/build-tools/">source: bootstrap.com</a>