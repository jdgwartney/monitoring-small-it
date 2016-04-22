#
# Generate a PDF preview of book contentds
#

chapters=*.md
book_file=book.pdf

book.pdf: $(chapters)
	pandoc -f markdown -o book.pdf $?

clean:
	$(RM) $(book_file)

