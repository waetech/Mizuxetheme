# Mizuxetheme
This is a website built with Bootstrap 4, jquery, html5, and css3.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-quiv="X-UA-Compatible" content="ie=edge">
    <title>Bootstrap 4 Starter Pack</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css">
    </head>
    <body id="home">
        <nav class="navbar navbar-expand-md navbar-light fixed-top py-4">
          <div class="container">
              <a href="#index.html" class="navbar-brand">
              <img src="img/mlogo.png" alt="" width="50" height="50"><h3 class="d-inline align-middle">Mizuxe</h3>
              </a>
             <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav"><span class="navbar-toggler-icon"></span></button>
              <div class="collapse navbar-collapse" id="navbarNav">
                 <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                       <a href="#home" class="nav-link">Home</a>
                     </li>
                       <li class="nav-item">
                       <a href="#about" class="nav-link">About</a>
                     </li>
                     <li class="nav-item">
                       <a href="#authors" class="nav-link">Meet the Authors</a>
                     </li>
                     <li class="nav-item">
                       <a href="#contact" class="nav-link">Contact</a>
                     </li>
                  </ul>
              </div>
            </div>
        </nav>
        
        
    <!--Showcase-->
        <section id="showcase" class="py-5">
         <div class="primary-overlay text-white">
            <div class="container">
              <div class="row">
                <div class="col-lg-6 text-center">
                  <h1 class="display-2 mt-5 pt-5">So What You Dream Of...
                    </h1>
                    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et, tempor leo.</p>
                    <a href="#" class="btn btn-oultine-secondary btn-lg text-white"><i class="fa fa-arrow-right"></i>Read More</a>
                  </div>
                  <div class="col-lg-6">
                   <img src="img/book.png" alt="" class="img-fluid d-none d-lg-block">
                  </div>
                </div>
             </div>
            </div>
        </section>
        
        <!--Newsletter-->
        <section id="newsletter" class="bg-dark text-white py-5">
        <div class="container">
            <div class="row">
              <div class="col-md-4">
                <input type="text" class="form-control form-control-lg" placeholder="Enter name">
                </div>
                <div class="col-md-4">
                <input type="text" class="form-control form-control-lg" placeholder="Enter Email">
                </div>
                <div class="col-md-4">
               <button class="btn btn-primary btn-lg btn-block"><i class="fa fa-envelope-open-o"></i> Subscribe</button>
                </div>
            </div>
            </div>
        </section>
        
        <!--Boxes-->
        <section id="boxes" class="py-5">
            <div class="container">
              <div class="row">
                 <div class="col-md-3">
                  <div class="card text-center border-primary">
                      <div class="body">
                       <h3 class="text-primary">Be Better</h3>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam ipsum</p>
                      </div>
                     </div>
                  </div>
                  <div class="col-md-3">
                  <div class="card text-center bg-primary text-white">
                      <div class="body">
                       <h3 class="text-light">Be Smarter</h3>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam ipsum</p>
                      </div>
                     </div>
                  </div>
                  <div class="col-md-3">
                  <div class="card text-center border-primary">
                      <div class="body">
                       <h3 class="text-primary">Be Faster</h3>
                          <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam ipsum</p>
                      </div>
                     </div>
                  </div>
                  <div class="col-md-3">
                  <div class="card text-center bg-primary text-white">
                      <div class="body">
                       <h3 class="text-light">Be Strong</h3>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.Aloqia, ipsum.</p>
                      </div>
                     </div>
                  </div>
                </div>
            </div>
        </section>
        
        <!--About-->
        <section id="about" class="my-5 py-5 text-center bg-light">
            <div class="container">
                <div class="row">
                   <div class="col">
                      <div class="info-header mb-5">
                        <h1 class="text-primary pb-3">Why This Book?</h1>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et.</p>
                       </div>
                       
                       <!--Accordion-->
                        <div id="accordion" role="tablist">
                            <div class="card">
                              <div class="card-header" id="heading1">
                                  <h5 class="mb-0">
                                  <div href="#collapse1" data-toggle="collapse" data-parent="#accordion">
                                      <i class="fa fa-arrow-circle-down"></i> Get Inspired</div>
                                  </h5>
                             </div>
                                <div id="#collapse1" class="collapse show">
                                 <div class="card-body">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et, tempor leo. Nam quis purus dictum, pretium neque vestibulum, tincidunt risus. Nunc vitae tempor massa, in eleifend odio. Vestibulum elementum congue quam nec lobortis. Etiam ultrices ac augue sed convallis. Nullam ac turpis ac mauris condimentum vehicula. Mauris fermentum, ante vel convallis tincidunt, sem tellus hendrerit diam, ut vestibulum mauris odio ac sapien. Duis urna dolor, convallis ac auctor nec, egestas in ex.
                                    </div>
                                </div>
                           </div>    
                            <div class="card">
                              <div class="card-header" id="heading2">
                                  <h5 class="mb-0">
                                  <div href="#collapse2" data-toggle="collapse" data-parent="#accordion">
                                      <i class="fa fa-arrow-circle-down"></i> Get Some Knowledge</div>
                                  </h5>
                             </div>
                                <div id="#collapse2" class="collapse show">
                                 <div class="card-body">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et, tempor leo. Nam quis purus dictum, pretium neque vestibulum, tincidunt risus. Nunc vitae tempor massa, in eleifend odio. Vestibulum elementum congue quam nec lobortis. Etiam ultrices ac augue sed convallis. Nullam ac turpis ac mauris condimentum vehicula. Mauris fermentum, ante vel convallis tincidunt, sem tellus hendrerit diam, ut vestibulum mauris odio ac sapien. Duis urna dolor, convallis ac auctor nec, egestas in ex.
                                    </div>
                                </div>
                           </div>    
                            <div class="card">
                              <div class="card-header" id="heading3">
                                  <h5 class="mb-0">
                                  <div href="#collapse3" data-toggle="collapse" data-parent="#accordion">
                                      <i class="fa fa-arrow-circle-down"></i> Open Your Mind</div>
                                  </h5>
                             </div>
                                <div id="#collapse3" class="collapse show">
                                 <div class="card-body">
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et, tempor leo. Nam quis purus dictum, pretium neque vestibulum, tincidunt risus. Nunc vitae tempor massa, in eleifend odio. Vestibulum elementum congue quam nec lobortis. Etiam ultrices ac augue sed convallis. Nullam ac turpis ac mauris condimentum vehicula. Mauris fermentum, ante vel convallis tincidunt, sem tellus hendrerit diam, ut vestibulum mauris odio ac sapien. Duis urna dolor, convallis ac auctor nec, egestas in ex.
                                    </div>
                                </div>
                           </div>    
                              
                    </div>
                       
                </div>
                </div>
            </div>
        </section>
        
        <!--AUTHORS-->
        
        <section id="authors" class="my-5 text-center">
            <div class="container">
              <div class="row">
                <div class="col">
                  <div class="info-header mb-5">
                        <h1 class="text-primary pb-3">Meet The Authors</h1>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam a tellus vestibulum, efficitur dolor et.</p>
                       </div>
                  </div>
            </div>
                <div class="row">
                  <div class="col-lg-3 col-md-6">
                    <div class="card">
                      <div class="card-body">
                        <img src="img/person1.jpg" alt="" class="img-fluid rounded-circle w-50 mb-3"> 
                          <h3>Susan Williams</h3>
                          <h5 class="text-muted">Lead Writer</h5>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                          <div class="d-flex flex-row justify-content-center">
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-facebook"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-twitter"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-instagram"></i>
                              </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-3 col-md-6">
                          <div class="card">
                      <div class="card-body">
                        <img src="img/person2.jpg" alt="" class="img-fluid rounded-circle w-50 mb-3"> 
                          <h3>Grace Smith</h3>
                          <h5 class="text-muted">Co Writer</h5>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                          <div class="d-flex flex-row justify-content-center">
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-facebook"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-twitter"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-instagram"></i>
                              </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-3 col-md-6">
                          <div class="card">
                      <div class="card-body">
                        <img src="img/person3.jpg" alt="" class="img-fluid rounded-circle w-50 mb-3"> 
                          <h3>John Doe</h3>
                          <h5 class="text-muted">Editor</h5>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                          <div class="d-flex flex-row justify-content-center">
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-facebook"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-twitter"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-instagram"></i>
                              </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-3 col-md-6">
                          <div class="card">
                      <div class="card-body">
                        <img src="img/person4.jpg" alt="" class="img-fluid rounded-circle w-50 mb-3"> 
                          <h3>Kevin Swanson</h3>
                          <h5 class="text-muted">Designer</h5>
                          <p class="lead pb-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                          <div class="d-flex flex-row justify-content-center">
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-facebook"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-twitter"></i>
                              </div>
                              <div class="p-4">
                                  <a href="#"></a><i class="fa fa-instagram"></i>
                              </div>
                          </div>
                        </div>
                      </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!--contact-->
        <section id="contact" class="bg-light py-5">
            <div class="container">
             <div class="row">
                <div class="col-lg-9">
                  <h3>Get In Touch</h3>
                    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <form>
                     <div class="form-group">
                        <div class="input-group input-group-lg">
                         <span class="input-group-addon"><i class="fa fa-user"></i></span><input type="text" class="form-control" placeholder="Name">
                         </div>
                        </div>
                        <div class="form-group">
                        <div class="input-group input-group-lg">
                         <span class="input-group-addon"><i class="fa fa-envelope"></i></span><input type="email" class="form-control" placeholder="Email">
                         </div>
                        </div>
                        <div class="form-group">
                        <div class="input-group input-group-lg">
                            <span class="input-group-addon"><i class="fa fa-pencil"></i></span><textarea class="form-control" placeholder="Message" rows="5"></textarea>
                         </div>
                        </div>
                        <input type="submit" value="submit" class="btn btn-primary btn-block btn-lg">
                    </form>
                 </div>
                 <div class="col-lg-3 align self-center">
                   <img src="img/mlogo.png" alt="" class="img-fluid">
                 </div>
                </div>
            </div>
        
        </section>
        
        <!--Footer-->
        <footer id="main-footer" class="py-5 bg-primary text-white">
            <div class="container">
              <div class="row text-center">
                <div class="col-md-6 ml-auto">
                  <p class="lead">Copyright &copy; 2018</p>
                  </div>
                </div>
            </div>
        
        </footer>
        
        
        
    <script src="js/jquery.min.js"></script>
     <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/navbar-fixed.js"></script>    
    
    </body>
</html>
