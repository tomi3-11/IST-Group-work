# Borrow_book Function
```python
    '''
    |--------------------------------------------------------|
    Algorithm
    1. Start
    2. REMARK: Function initialization; def borrow_book()
    3. set book = find_book()
    4. if book not found, display "Book not found
    5. if book not available, display "Book already borrowed"
    6. set book['available'] = False
    7. borrower = borrower name and email
    8. due_date = current date + the loan period
    9. REMARK: Add the book to the borrowed_books array.
    10. Stop

    |--------------------------------------------------------|
    Pseudocode
    BEGIN
        COMMENT: Initialization of function borrow_book
        book = find_book() COMMENT: setup the book variable
        IF not book: DISPLAY: "Book not found"
        RETURN False
        IF not book['available']: DISPLAY: "Book is already borrowed.
        RETURN False
        book availability = False
        borrower = borrower_name and email
        due_date = current_date + loan_period
        COMMENT: Add the book to the borrowed_books array
        DISPLAY: "Book borrowed successfully
        RETURN True
    END

    '''

```

# Return Book Function
```python
    '''
    |---------------------------------------------------------------|

    Algorithm
    1. Start
    2. REMARK: Initialization fo the return_book() function
    3. set book = find_book()
    4. if book not found, display "Book not found
    5. if book not available, display "Book alread borrowed"
    6. set book availability = True
    7. REMARK: remove the borrower
    8. REMARK: remove the due_date
    9. FOR: Loop through the borrowed_books array
    10. if the user isbn == isbn in borrowed_books
    11. REMARK: remove the book from borrowed_books
    12. REMARK: break out of the loop
    13. Stop

    |---------------------------------------------------------------|

    Pseudocode
    BEGIN
        COMMENT: Initialization fo the return_book() function
        book = find_book()
        If book not found: DISPLAY "Book not found
        If book not available: DISPLAY "Book already borrowed"
        book availability = True COMMENT: Change book status
        COMMENT: remove the borrower
        COMMENT: remove the due_date
        FOR: Loop through the borrowed_books array
        If the user isbn == isbn:
        COMMENT: remove the book from borrowed_books
        COMMENT: break out of the loop
        DISPLAY: "Book 'book['title']' return by book['borrower']
    END
    '''
```