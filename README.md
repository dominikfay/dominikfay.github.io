<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <title>Don de Sang</title>
    <style>
        header{
    background-color: red;
}

#nav-home-tab{
    font-weight: bolder !important;
}

#nav-profile-tab{
    font-weight: bolder !important;
}

#nav-contact-tab{
    font-weight: bolder !important;
}

section{
    width: 50%;
    margin: auto;
    margin-top: 100px;
}

h1{
    text-align: center;
    color: red;
}

article{
    margin-top: 100px;
}

.formulaire{
    width: 80%;
    margin: auto;
    margin-top: 100px;
}

footer{
    background-color: red;
}

button{
    background-color: red !important;
    border: 0 !important;
    color: white !important;
}

a{
    color: red ;
    text-decoration: none;
}
h2{
    text-align: center;
    color: red;
    font-weight: bolder;
}

.nav-link{
    color: white !important;
}

.text-center{
    color: white !important;
}
    </style>
  </head>
  <body>
    <header>
        <nav>
            <div class="nav nav-tabs" id="nav-tab" role="tablist">
            <button class="nav-link active" id="nav-home-tab" data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home" aria-selected="true">Home</button>
            <button class="nav-link" id="nav-profile-tab" data-bs-toggle="tab" data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile" aria-selected="false">Profile</button>
            <button class="nav-link" id="nav-contact-tab" data-bs-toggle="tab" data-bs-target="#nav-contact" type="button" role="tab" aria-controls="nav-contact" aria-selected="false">Contact</button>
            </div>
        </nav>
        <div class="tab-content" id="nav-tabContent">
            <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">...</div>
            <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab">...</div>
            <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab">...</div>
        </div>
        </header>

        <main>
            <section>
                <h1>Conditions de don</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem dolorum inventore soluta adipisci, aperiam quisquam mollitia explicabo quia fugiat exercitationem nemo asperiores dicta! Tempore quas, mollitia eaque nobis facilis eligendi? Lorem ipsum dolor sit amet consectetur, adipisicing elit. Optio, dignissimos molestiae nostrum officia, fugit aperiam odit impedit consequuntur animi reiciendis harum eligendi laudantium autem non laboriosam vel dolorum culpa error. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat necessitatibus, sed deserunt sit optio pariatur cum saepe adipisci molestias corporis non sunt amet ab dicta quidem reiciendis ipsum, sapiente accusantium? Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatibus neque quibusdam aut quidem facilis error tempora inventore provident! Inventore dolor porro aspernatur aut error hic totam ex tempore quae doloremque?</p>
                <div class="d-grid gap-2 col-6 mx-auto">
                    <button class="btn btn-primary" type="button">J'accepte</button>
                </div>
            </section>
            
            <article>
                <div class="container">
                    <div class="row">
                    <div class="col">
                        <h2><a href="#">Groupes Sanguins</a></h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum voluptates adipisci voluptatibus ipsum provident laborum commodi repudiandae veritatis quam non ea vitae, animi, at quia aut numquam? Sed, repellendus quibusdam.</p>
                    </div>
                    <div class="col">
                        <h2><a href="#">Modalités</a></h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum voluptates adipisci voluptatibus ipsum provident laborum commodi repudiandae veritatis quam non ea vitae, animi, at quia aut numquam? Sed, repellendus quibusdam.</p>
                    </div>
                    <div class="col">
                        <h2><a href="#">Où Aller ?</a></h2>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum voluptates adipisci voluptatibus ipsum provident laborum commodi repudiandae veritatis quam non ea vitae, animi, at quia aut numquam? Sed, repellendus quibusdam.</p>
                    </div>
                    </div>
                </div>
            </article>

            <aside class="formulaire">
                <form class="row g-3">
                        <legend><h3>Remplissez ce formulaire</h3></legend>
                    <div class="col-md-4">
                    <label for="validationDefault01" class="form-label">Prénom</label>
                    <input type="text" class="form-control" id="validationDefault01"  required>
                    </div>
                    <div class="col-md-4">
                    <label for="validationDefault02" class="form-label">Nom</label>
                    <input type="text" class="form-control" id="validationDefault02"  required>
                    </div>
                    <div class="col-md-4">
                        <label for="validationDefault01" class="form-label">Age</label>
                        <input type="text" class="form-control" id="validationDefault01"  required>
                        </div>
                    <div class="col-md-4">
                    <label for="validationDefaultUsername" class="form-label">E-mail</label>
                    <div class="input-group">
                        <input type="text" class="form-control" id="validationDefaultUsername"  aria-describedby="inputGroupPrepend2" required>
                    </div>
                    </div>
                    <div class="col-md-3">
                        <label for="validationDefault04" class="form-label">Pays</label>
                        <select class="form-select" id="validationDefault04" required>
                            <option selected disabled value="">Sénégal</option>
                            <option>Gambie</option>
                            <option>Mali</option>
                            <option>Côte d'Ivoire</option>
                        </select>
                        </div>
                    <div class="col-md-6">
                    <label for="validationDefault03" class="form-label">Ville</label>
                    <select class="form-select" id="validationDefault04" required>
                        <option selected disabled value="">Kaffrine</option>
                        <option>Malhem Hodar</option>
                        <option>Koungheul</option>
                        <option>Mbirkilane</option>
                    </select>
                    </div>
                    <div class="col-md-3">
                    <label for="validationDefault04" class="form-label">Groupe Sanguin</label>
                    <select class="form-select" id="validationDefault04" required>
                        <option selected disabled value="">A+</option>
                        <option>A-</option>
                        <option>B+</option>
                        <option>B-</option>
                        <option>O</option>
                    </select>
                    </div>         
                    <div class="col-12">
                    <div class="form-check">
                        <input class="form-check-input" type="checkbox" value="" id="invalidCheck2" required>
                        <label class="form-check-label" for="invalidCheck2">
                        Agree to terms and conditions
                        </label>
                    </div>
                    </div>
                    <div class="col-12">
                    <button class="btn btn-primary" type="submit">Submit form</button>
                    </div>
                </form>
            </aside>
        </main>

        <footer>
            <div class="container">
                <footer class="py-3 my-4">
                  <ul class="nav justify-content-center border-bottom pb-3 mb-3">
                    <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Home</a></li>
                    <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Features</a></li>
                    <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Pricing</a></li>
                    <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">FAQs</a></li>
                    <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">About</a></li>
                  </ul>
                  <p class="text-center text-muted">&copy; 2021 Company, Inc</p>
                </footer>
              </div>
        </footer>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
