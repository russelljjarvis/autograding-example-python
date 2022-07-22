# Autograding Example: Python
This example project is written in Python, and tested with pytest.

### The assignment
The tests are failing right now because the method isn't outputting the correct string. Fixing this up will make the tests green.

# Passing the assignment
* Making the tests green on your local computer, git commiting the tests and then pushing the code will mean that you pass the assignment and the instructors can see that you pass on our end.

### Setup command
# on Ubuntu:
`sudo -H $(which pip) install pytest`
# on Apple:
`sudo -H $(which pip) install pytest`
# on Windows/Gitbash:
Let us know if you use gitbash and we will come to you.
### Run command
`pytest`

### Notes
- pip's install path is not included in the PATH var by default, so without installing via `sudo -H`, pytest would be unaccessible.
