C=asciidoctor-pdf

FILE1=resume.adoc
DEPS1=$(FILE)
OUT1=resume.pdf

FILE2=curriculum.adoc
DEPS2=$(FILE)
OUT2=curriculum.pdf

all: $(OUT1) $(OUT2)

$(OUT1): $(DEPS1)
	$(C) $(FILE1)

$(OUT2): $(DEPS2)
	$(C) $(FILE2)

clean:
	rm $(OUT1) $(OUT2)
