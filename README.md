```shell
    pip install build
    python -m build
 
    # create virtual environment
    $ python3 -m venv .env/fresh-install-test
    
    # activate your virtual environment
    $ . .env/fresh-install-test/bin/activate
    
    # install your package into this fresh environment
    $ pip install dist/mypackage-0.0.0-py3-none-any.whl
    
    # your shortcuts are now in the venv bin directory
    $ ls .env/fresh-install-test/bin/
    my-application
    another-application
    
    # so you can run it directly from the cli
    $ my-application
    hello from my_function
    
    # and run the second application
    $ another-application
    hello from another_function
  
```