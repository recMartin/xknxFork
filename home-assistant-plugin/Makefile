
help:
	@echo ""
	@echo "Available targets:"
	@echo ""
	@echo "install             will copy plugin to plugindirectory .homeassistant/custom_components"
	@echo ""
	@echo "pylint              run pylint tests"
	@echo ""

install:
	mkdir -p ~/.homeassistant
	ln -s `pwd`/custom_components ~/.homeassistant

pylint:
	pylint --rcfile=.pylintrc custom_components/*/*.py


