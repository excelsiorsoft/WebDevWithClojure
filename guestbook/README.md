# guestbook

An example

## Prerequisites

You will need [Leiningen][1] 1.7.0 or above installed.

[1]: https://github.com/technomancy/leiningen

## Running

To start a web server for the application, run:

    lein ring server
    
## Running In Eclipse:
    
	;; Clojure 1.6.0
	=> (use 'guestbook.repl)  
	nil  


see http://stackoverflow.com/questions/20828985/compilerexception-java-lang-runtimeexception-unable-to-resolve-symbol-cloju for explanation   

	> (require :reload 'guestbook.repl)  
	nil  

	> (start-server)  

	guestbook is starting  
	Started server on port 8080  
	You can view the site at http://localhost:8080  
	nil

## License

Copyright © 2015 FIXME
