build_sws: build_ht tex2sws

tex2sws: practical_discrete.html practical_discrete.css
	$(HOME)/tex2sws/tex2sws.py

build_ht: practical_discrete.tex */*.tex
	htlatex practical_discrete.tex "$(HOME)/tex2sws/tex4ht-sage.cfg" " -cunihtf -utf8"
