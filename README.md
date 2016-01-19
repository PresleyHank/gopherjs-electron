# gopherjs-electron
Atom/Electron desktop apps with Go. Package use https://github.com/gopherjs/gopherjs.

[![Build Status](https://travis-ci.org/arvitaly/gopherjs-electron.svg?branch=master)](https://travis-ci.org/arvitaly/gopherjs-electron)

Install

Package require electron-prebuilt npm-module

	npm install -g electron-prebuilt

	go get github.com/arvitaly/gopherjs-electron

For tests used Jasmine (http://jasmine.github.io/) and adapter fo go https://github.com/arvitaly/gopherjs-jasmine

	go get github.com/arvitaly/gopherjs-jasmine
	npm install
	npm test

Also you can use docker-image for electron (includes NodeJS, Golang, gopherjs, electron-prebuilt). Example for run app in docker-container in file .drone.yml (config for drone.io CI)

	docker pull arvitaly/electron-go
