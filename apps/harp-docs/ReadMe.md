# harp --help

Harp 〜 Static Web Server/Generator/Bundler v0.46.1

## Usage

harp `<source>` serves project locally
harp `<source>` `<build>` compiles for static host

## Options

-p, --port 9000 server port to listen on
-h, --host 0.0.0.0 server host to answer to
-s, --silent false supresses logs
-h, --help outputs this help message
-v, --version outputs version of harp

<br>

| Processing | Data
|-- | --
| .ejs -> .html | \_data.json - directory data
| .jade -> .html | \_data.js - dynamic build data
| .md -> .html | --
| .sass -> .css | GENERATION
| .scss -> .css | partial("\_path/to/partial", {
| .cjs -> .js | "title": "Hello World"
| .jsx -> .js | })
