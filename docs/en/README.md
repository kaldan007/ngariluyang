

<!DOCTYPE html>
<html>
<head>


<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Style the buttons */
.btn {
  border: none;
  outline: none;
  padding: 12px 16px;
  background-color: #f1f1f1;
  cursor: pointer;
}

.btn:hover {
  background-color: #ddd;
}

.btn.active {
  background-color: #666;
  color: white;
}
</style>
</head>
<body>

<h1>མངའ་རིས་གླུ་དབྱངས།</h1>
<div class="row">
  <div class="column" style="background-color:#aaa;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat1.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Shung Lu</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
  <div class="column" style="background-color:#bbb;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat2.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Bak Lu</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
</div>

<div class="row">
  <div class="column" style="background-color:#ccc;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat3.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Shab dho</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
  <div class="column" style="background-color:#ddd;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat4.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Chang Lu</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="column" style="background-color:#aaa;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat5.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Zha Lu</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
  <div class="column" style="background-color:#bbb;">
    <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="_assets/categories/cat6.png" alt="Card image cap">
        <div class="card-body">
            <h5 class="card-title">Tseg Lu</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
  </div>
</div>
</body>
</html>