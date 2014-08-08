Lo-Dash is an alternative to Underscore. Its API closely matches Underscore's, but Lo-Dash was designed to be more flexible, allowing you to use [custom builds](http://lodash.com/custom-builds) that include only the functions you need without having to include the entire library as a dependency. When building a server-side Node application, using larger npm packages is not much of a problem, but as you start to use tools like browserify to build browser applications using npm packages, filesize becomes an important concern.