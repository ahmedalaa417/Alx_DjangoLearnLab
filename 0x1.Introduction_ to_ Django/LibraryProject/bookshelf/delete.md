from bookshelf.models import Book
Command:
book.delete()
books = Book.objects.all()
print(books)

Output:
<QuerySet []>
