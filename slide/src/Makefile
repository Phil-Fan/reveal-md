.PHONY: live build clean

all: live-dark
# Build live dark slides by default

live:
	@echo "Previewing main slides..."
	@reveal-md main.md -w --scripts https://cdn.tonycrane.cc/heti/heti.js,./static/heti_worker.js --template ./static/template.html || true

build:
	@echo "Building main slides..."
	@reveal-md main.md --scripts https://cdn.tonycrane.cc/heti/heti.js,./static/heti_worker.js --template ./static/template.html --static ../site --assets-dir assets
	@rm ../site/main.html

build-dark:
	@echo "Building dark slides..."
	@reveal-md main.dark.md --scripts https://cdn.tonycrane.cc/heti/heti.js,./static/heti_worker.js --template ./static/template.html --static ../site --assets-dir assets
	@rm ../site/main.html

live-dark:
	@echo "Previewing dark slides..."
	@reveal-md main.dark.md -w --scripts https://cdn.tonycrane.cc/heti/heti.js,./static/heti_worker.js --template ./static/template.html || true

clean:
	@echo "Cleaning up..."
	rm -rf ../site/
