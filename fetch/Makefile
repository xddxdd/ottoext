all: js/bundle.js

js/bundle.js: js/fetch.js js/headers.js js/index.js js/request.js js/response.js
	cd js && npm install && npm run bundle${BUNDLE_SUFFIX}

clean:
	rm -rf dist-fetch.rice-box.go dist-fetch js/bundle.js
