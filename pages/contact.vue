<template>
    <main>
        <navbar/>
        <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css"/>
        <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
        <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
        <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-T8Gy5hrqNKT+hzMclPo118YTQO6cYprQmhrYwIiQ/3axmI1hQomh7Ud2hPOy8SP1" crossorigin="anonymous"/>

        <section class="contact py-5 bg-light" id="contact">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <h4>Contact Us </h4>
                    <hr>
                </div>
                <div class="col-md-6">
                    <div class="address">
                        
                    <h5>Address:</h5>
                    <ul class="list-unstyled">
                        <li>Kota</li>
                        <li>Wilayah</li>
                        <li>Negara</li>
                    </ul>
                    <p></p>
                    </div>
                    <div class="email">
                    <h5></h5>
                    <ul class="list-unstyled">
                        <li> Your@email.com</li>
                        <li> Your@email.com</li>
                    </ul>
                    </div>
                    <div class="phone">
                        <h5>Phone:</h5>
                        <ul class="list-unstyled">
                        <li> +62- 8XXXXXXXXXXXX</li>
                        <li> +62- 8XXXXXXXXXXXX</li>
                    </ul>
                    </div>
                    <hr>
                    <div class="social">
                    <ul class="list-inline list-unstyled">
                        <li class="list-inline-item">
                            <a href="#"><i class="fa fa-facebook"></i></a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#"><i class="fa fa-instagram"></i></a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#"><i class="fa fa-whatsapp"></i></a>
                        </li>
                    </ul>
                </div>
                </div>
                <div class="col-md-6">
                    <div class="card">
                        <div class="card-body">
                            <form>
                                <div class="form-row">
                                    <div class="form-group col-md-6">
                                    <input id="Full Name" name="Full Name" placeholder="Full Name" class="form-control" type="text">
                                    </div>
                                    <div class="form-group col-md-6">
                                    <input type="email" class="form-control" id="inputEmail4" placeholder="Email">
                                    </div>
                                </div>
                                <div class="form-row">
                                    <div class="form-group col-md-6">
                                        <input id="Mobile No." name="Mobile No." placeholder="Mobile No." class="form-control" required="required" type="text">
                                    </div>
                                    <div class="form-group col-md-6">
                                            
                                            <select id="inputState" class="form-control">
                                                <option selected>Choose ...</option>
                                                <option> Order</option>
                                                <option> Complaint</option>
                                                <option> Feedback</option>
                                            </select>
                                    </div>
                                    <div class="form-group col-md-12">
                                            <textarea id="comment" name="comment" cols="40" rows="5" placeholder="Your Message" class="form-control"></textarea>
                                    </div>
                                </div>
                                
                                <div class="form-row">
                                    <button type="button" class="btn btn-danger">Submit</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            
            
        </div>
        </section>
    </main>
</template>
