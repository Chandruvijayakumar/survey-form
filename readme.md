Task 1 is Survey form
++ HTML code 
<!-- <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Survey Form</title>
        <link rel="stylesheet" href="./survey.css">
        <link
            href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
            rel="stylesheet">
        <link rel="stylesheet"
            href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
                <link rel="stylesheet" href="//netdna.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css">
    CSS only<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
   <!-- JavaScript Bundle with Popper --><script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" 
   <!-- integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>          -->
    <!-- </head> -->
    <!-- <body> -->
        <!-- <div class="container bg-black.bg-gradient border border-danger"> -->

            <!-- <div class="mb-3 fw-bolder text-center"> -->
                <!-- <h1 class="text-center p-3 mb-2 bg-success-subtle text-emphasis-success text-uppercase ">Survey Form</h1>
                <h3 class="form-control form-control-lg">Introduction to Programming</h3>
                <p class="form-control form-control-lg">This form attempts to quantify user satisfaction with the
                    platform.The feedback will be used to
                    improve the curriculum.</p>
            </div>
            <div>
                <div class="mb-3 fw-bolder ">
                    <label for="exampleFormControlInput1"
                        class="form-label">Name</label>
                    <input type="text" class="form-control"
                        id="exampleFormControlInput1"
                        placeholder="Enter Your Name">
                </div>
                <div class="mb-10 fw-bolder">
                    <label for="exampleFormControlInput1"
                        class="form-label">Email address</label>
                    <input type="email" class="form-control"
                        id="exampleFormControlInput1"
                        placeholder="name@example.com">
                </div>
                <div class="mb-3 fw-bolder">
                    <label for="exampleFormControlInput1"
                        class="form-label">Mobile Number</label>
                    <input type="tel" class="form-control"
                        id="exampleFormControlInput1"
                        placeholder="Enter your Mobile Number">
                </div>
                <div class="mb-3 fw-bolder">
                    <p>What best describe your CTC </p>
                    <select class="form-select"
                        aria-label="Default select example">
                        <option
                            selected>Select your Salary</option>
                        <option value="1">Above 3LPA</option>
                        <option value="2">Above 5LPA</option>
                        <option value="3">Above 7LPA</option>
                    </select>
                </div>
                <div class="mb-3 fw-bolder">
                    <p>Yor looking For a Current Role </p>
                    <select class="form-select"
                        aria-label="Default select example">
                        <option
                            selected>Select your Salary</option>
                        <option value="1">Working</option>
                        <option value="2">Searching for a job</option>
                        <option value="3">Final Year</option>
                    </select>
                </div>
                <div class="mb-3 fw-bolder">
                    <h3>Type of Programming interested in:</h3>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio"
                        name="flexRadioDefault" id="flexRadioDefault1">
                        <label class="form-check-label" for="flexRadioDefault1">
                        Functional
                    </label>
                </div>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio"
                    name="flexRadioDefault" id="flexRadioDefault1">
                <label class="form-check-label" for="flexRadioDefault1">
                    Declarative
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="radio"
                    name="flexRadioDefault" id="flexRadioDefault1">
                <label class="form-check-label" for="flexRadioDefault1">
                    object oriented
                </label>
            </div>

            <div class="mb-3 fw-bolder">
                <h3>Programming language of interested :</h3>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    C++
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    Java
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    Python
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    Ruby
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    .Net
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    JavaScript
                </label>
            </div>
            <div class="form-check">
                <input class="form-check-input" type="checkbox" value
                    id="defaultCheck1">
                <label class="form-check-label" for="defaultCheck1">
                    PHP
                </label>
            </div>
            <h3>Your Experience<label class="red">*</label></h3>
            <p><b></b>how would you rate you with us</p>
         <div class="rating">
            <div class="stars">
                <form action="">
                  <input class="star star-5" id="star-5" type="radio" name="star"/>
                  <label class="star star-5" for="star-5"></label>
                  <input class="star star-4" id="star-4" type="radio" name="star"/>
                  <label class="star star-4" for="star-4"></label>
                  <input class="star star-3" id="star-3" type="radio" name="star"/>
                  <label class="star star-3" for="star-3"></label>
                  <input class="star star-2" id="star-2" type="radio" name="star"/>
                  <label class="star star-2" for="star-2"></label>
                  <input class="star star-1" id="star-1" type="radio" name="star"/>
                  <label class="star star-1" for="star-1"></label>
                </form>
              </div>    
         </div>
            <div class="mb-3 fw-bolder">
                <label for="exampleFormControlTextarea1"
                    class="form-label">Additional Information</label>
                <textarea class="form-control"
                    id="exampleFormControlTextarea1" rows="3"></textarea>
            </div>
            <div class="text-center">
                <button type="button" class="btn btn-primary">Submit</button>
            </div>
            </div>
        </div>
        <script
            src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
                <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
        <script
            src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
        <script
            src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
        </body>
</html> --> -->
===================================================================================================================================================
++ css code

.bg-black.bg-gradient {
    --bs-bg-opacity: 1;
    background-color: rgba(var(--bs-success-rgb), var(--bs-bg-opacity)) !important;
}
.container{
    background-color:rgba(83, 83, 83, 0.608);
 }
.last {
    position: absolute;
    top: 60px;
    left: 200px;
}

div.stars {
    width: 270px;
    display: inline-block;
}

input.star {
    display: none;
}

label.star {
    float: right;
    padding: 10px;
    font-size: 36px;
    color: #444;
    transition: all .2s;
}

input.star:checked~label.star:before {
    content: '\f005';
    color: #FD4;
    transition: all .25s;
}

input.star-5:checked~label.star:before {
    color: #FE7;
    text-shadow: 0 0 20px #952;
}

input.star-1:checked~label.star:before {
    color: #F62;
}


label.star:before {
    content: '\f005';
    font-family: FontAwesome;
}

.red {
    color: red;
}


.col-5 {
    display: grid;
    grid-template-columns: 30% 30% 30% 30% 30%;
    position: absolute;
    left: 25%;
    justify-content: space-between;
}

.col-6 {
    display: grid;
    grid-template-columns: 40% 30% 20% 25% 30% 25%;
    position: absolute;
}

.form {
    background-color: rgb(8, 91, 91);
    color: rgb(233, 192, 6);

}