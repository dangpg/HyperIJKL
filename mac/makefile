compile:
	yq hyperijkl.yml -o=json > hyperijkl.json

install: compile
	mkdir -p $$HOME/.config/karabiner/assets/complex_modifications/
	cp HyperIJKL.json $$HOME/.config/karabiner/assets/complex_modifications/

.PHONY: compile,install
