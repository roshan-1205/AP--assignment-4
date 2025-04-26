# AP--assignment-4
Program to create a Book class with attributes title and author and a method to display book information.


    public class Book {
	
    private String title;
    private String author;

    public Book(String title, String author) {
        this.title = title;
        this.author = author;
    }

    public void displayInfo() {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
    }

    public static void main(String[] args) {
        Book book1 = new Book("In The Silence You Left Behind", "Sumitra Manda");
        book1.displayInfo();
    }
}
