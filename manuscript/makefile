#
# Generate a PDF preview of book contentds
#

chapters=*.md
book=monitoring-small-it.pdf

$(book): $(chapters)
	pandoc -f markdown -o $(book) $?

clean:
	$(RM) $(book)

