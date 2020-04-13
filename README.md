<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <link rel="stylesheet" href="all.css">
        <link rel="stylesheet" href="https://bootswatch.com/4/yeti/bootstrap.min.css"> 
        
        
        <title>MyBookList App</title>        
    </head>
    <body>
        <div class="container mt-4">
            <h1 class="display-4 text-center">            
            <i class="fas fa-book-open text-primary"></i> My<span class="text-primary">Book</span>List</h1>
            <form id="book-form">
                <div class="form-group">
                    <label for="title">Title</label>
                    <input type="text" id="title" class="form-control">
                </div>
                <div class="form-group">
                    <label for="author">Author</label>
                    <input type="text" id="author" class="form-control">
                </div>
                <div class="form-group">
                    <label for="isbn">ISBN#</label>
                    <input type="text" id="isbn" class="form-control">
                </div>
                <input type="submit" value="Add Book" class="btn btn-primary btn-block">
            </form>
            <table class="table table-striped mt-5">
                <thead>
                    <tr>
                        <th>Title</th>
                        <th>Author</th>
                        <th>ISBN#</th>
                        <th></th>
                    </tr>
                </thead>
                <tbody id="book-list"></tbody>
            </table>
        </div>  
        
        <script src="https://kit.fontawesome.com/f7d9e3b3c9.js" crossorigin="anonymous"></script>
        <script src="main.js"></script>
    </body>
</html>
