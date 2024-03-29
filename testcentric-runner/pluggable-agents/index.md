﻿<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=Edge" />
        <meta name="description" />
        <meta name="keywords" content="static content generator,static site generator,static site,HTML,web development,.NET,C#,Razor,Markdown,YAML" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="shortcut icon" href="/assets/img/favicon.ico" type="image/x-icon">
        <link rel="icon" href="/assets/img/favicon.ico" type="image/x-icon">
        <title>TestCentric - Pluggable Agents</title>
        <link href="/assets/css/highlight.css" rel="stylesheet">
        <link href="/assets/css/bootstrap/bootstrap.css" rel="stylesheet" />
        <link href="/assets/css/adminlte/AdminLTE.css" rel="stylesheet" />
        <link href="/assets/css/theme/theme.css" rel="stylesheet" />
        <link href="//fonts.googleapis.com/css?family=Roboto+Mono:400,700|Roboto:400,400i,700,700i" rel="stylesheet">
        <link href="/assets/css/font-awesome.min.css" rel="stylesheet" type="text/css">
        <link href="/assets/css/override.css" rel="stylesheet" />
        <script src="/assets/js/jquery-2.2.3.min.js"></script>
        <script src="/assets/js/bootstrap.min.js"></script>        
        <script src="/assets/js/app.min.js"></script>         
        <script src="/assets/js/highlight.pack.js"></script>   
        <script src="/assets/js/jquery.slimscroll.min.js"></script>
        <script src="/assets/js/jquery.sticky-kit.min.js"></script>
        <script src="/assets/js/mermaid.min.js"></script>
        <script src="/assets/js/svg-pan-zoom.min.js"></script>
        <!--[if lt IE 9]>
        <script src="/assets/js/html5shiv.min.js"></script>
        <script src="/assets/js/respond.min.js"></script>
        <![endif]-->  

        
    </head>
    <body class="hold-transition wyam layout-boxed  ">    
        <div class="top-banner"></div>
        <div class="wrapper with-container">
            <!-- Header -->
            <header class="main-header">   
                     
                <a href="/" class="logo">

                                <!-- mini logo for sidebar mini 50x50 pixels -->
                                <span class="logo-mini"><img src="/assets/img/testcentriclogo.png"></span>
                                <!-- logo for regular state and mobile devices -->
                                <span class="logo-lg"><img src="/assets/img/testcentriclogo.png"></span>
                                            </a>   
                         
                <nav class="navbar navbar-static-top" role="navigation">
                    <!-- Sidebar toggle button-->
                        <a href="#" class="sidebar-toggle visible-xs-block" data-toggle="offcanvas" role="button">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-right"></i>
                        </a>
                                        
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-down"></i>
                        </button>
                    </div>
            
                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class="collapse navbar-collapse pull-left" id="navbar-collapse">
                        <ul class="nav navbar-nav">                            
                                        <li><a href="/">Home</a></li>
            <li class="active"><a href="/testcentric-runner">TestCentric Runner</a></li>
            <li><a href="/tc-lite">TC-Lite Framework</a></li>
            <li><a href="/blog">Blog</a></li>
 
                        </ul>       
                    </div>
                    <!-- /.navbar-collapse -->
                
                    <!-- Navbar Right Menu -->
                </nav>
            </header>
            
            <!-- Left side column. contains the logo and sidebar -->
            <aside class="main-sidebar ">
                <section class="infobar" data-spy="affix" data-offset-top="60" data-offset-bottom="200"> 
                    	
    <div id="infobar-headings"></div>

                </section>
                <section class="sidebar">    
                                     
                    

                    <ul class="sidebar-menu">
                        

                <li class="treeview">
                    <a href="#">TestCentric Runner</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-gui/overview">Overview</a></li>
                <li class="treeview">
                    <a href="/testcentric-runner/testcentric-gui/GettingStarted">Getting Started</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-gui/GettingStarted/installation">Installing the GUI</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/GettingStarted/starting">Starting the GUI</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/GettingStarted/running-tests">Running Tests</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/GettingStarted/stopping-tests">Stopping a Test Run</a></li>

                    </ul>
                </li>
                <li class="treeview">
                    <a href="/testcentric-runner/testcentric-gui/Features">GUI Elements</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-gui/Features/main-window">Main Window</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/main-menu">Main Menu</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/context-menu">Context Menu</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/mini-gui">Mini-Gui</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/settings-dialog">Settings Dialog</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/extensions-dialog">Extensions Dialog</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/Features/test-properties">Test Properties</a></li>

                    </ul>
                </li>
                <li><a href="/testcentric-runner/testcentric-gui/command-line">Command Line</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/release-notes">Release Notes</a></li>
                <li><a href="/testcentric-runner/testcentric-gui/license">License</a></li>

                    </ul>
                </li>
                <li class="treeview">
                    <a href="#">TestCentric Engine</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-engine/overview">Overview</a></li>
                <li class="treeview">
                    <a href="/testcentric-runner/testcentric-engine/engine-api">Engine API</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-engine/engine-api/test-engine-activator">Test Engine Activator</a></li>
                <li class="treeview">
                    <a href="#">Interfaces</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/testcentric-engine/engine-api/interfaces/test-engine">ITestEngine</a></li>
                <li><a href="/testcentric-runner/testcentric-engine/engine-api/interfaces/test-runner">ITestRunner</a></li>
                <li><a href="/testcentric-runner/testcentric-engine/engine-api/interfaces/service-locator">IServiceLocator</a></li>
                <li><a href="/testcentric-runner/testcentric-engine/engine-api/interfaces/agent-launcher">IAgentLauncher</a></li>

                    </ul>
                </li>

                    </ul>
                </li>
                <li><a href="/testcentric-runner/testcentric-engine/release-notes">Release Notes</a></li>
                <li><a href="/testcentric-runner/testcentric-engine/license">License</a></li>

                    </ul>
                </li>
                <li class="treeview active selected">
                    <a href="#">Pluggable Agents</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                        
                <li><a href="/testcentric-runner/pluggable-agents/overview">Overview</a></li>
                <li><a href="/testcentric-runner/pluggable-agents/available-agents">Available Agents</a></li>

                    </ul>
                </li>

                    </ul>
                            
                </section>                
            </aside>
            
            <!-- Content Wrapper. Contains page content -->
            <div class="content-wrapper">
                



		<section class="content-header">
			<h1>Pluggable Agents</h1>
		</section>
	<section class="content">
		
	</section>
                
            </div>           
            
            <!-- Footer -->
            <footer class="main-footer">
            </footer>
            
        </div>
        <div class="wrapper bottom-wrapper">
            <footer class="bottom-footer">
                Generated by <a href="https://wyam.io">Wyam</a>
            </footer>
        </div>
        <a href="javascript:" id="return-to-top"><i class="fa fa-chevron-up"></i></a>
        
        <script>           
            // Close the sidebar if we select an anchor link
            $(".main-sidebar a[href^='#']:not('.expand')").click(function(){
                $(document.body).removeClass('sidebar-open');
            });
            
            $(document).ready(function() {
                mermaid.initialize(
                {
                    flowchart:
                    {
                        useMaxWidth: false
                    },
					startOnLoad: false,
					cloneCssStyles: false
                });     
                mermaid.init(undefined, ".mermaid");

                // Remove the max-width setting that Mermaid sets
                var mermaidSvg = $('.mermaid svg');
                mermaidSvg.addClass('img-responsive');
                mermaidSvg.css('max-width', '');

                // Make it scrollable
				var target = document.querySelector(".mermaid svg");
				if(target !== null)
				{
					var panZoom = window.panZoom = svgPanZoom(target, {
						zoomEnabled: true,
						controlIconsEnabled: true,
						fit: true,
						center: true,
                        maxZoom: 20,
                        zoomScaleSensitivity: 0.6
					});			                          

                    // Do the reset once right away to fit the diagram
                    panZoom.resize();
                    panZoom.fit();
                    panZoom.center();
                    
                    $(window).resize(function(){
                        panZoom.resize();
                        panZoom.fit();
                        panZoom.center();
                    });
				}
                
                $('pre code').each(function(i, block) {
                    hljs.highlightBlock(block);
                });  
            });

            hljs.initHighlightingOnLoad();

            // Back to top
            $(window).scroll(function() {
                if ($(this).scrollTop() >= 200) {        // If page is scrolled more than 50px
                    $('#return-to-top').fadeIn(1000);    // Fade in the arrow
                } else {
                    $('#return-to-top').fadeOut(1000);   // Else fade out the arrow
                }
            });
            $('#return-to-top').click(function() {      // When arrow is clicked
                $('body,html').animate({
                    scrollTop : 0                       // Scroll to top of body
                }, 500);
            });
        </script>
    </body>
</html>