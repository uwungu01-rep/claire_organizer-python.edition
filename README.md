# Claire Organizer - Python Edition
(Don't judge me, I'm outta names) <br/>
A command line file organizer made. My largest project as of the creation of this repository.

## Functionalities
Organize the content of a folder, with various option, these include:
1. Configure the file types of a category.
2. Add/Remove a category of file types.

## Installation
<ol type="1">
  <li>
    Install Python 3.x from <a href="https://www.python.org/downloads/">here</a>. (Ignore if you already have Python 3.x installed)
  </li>
  <li>
    Open terminal, run:
    
```
pip install claire_organizer
```
  </li>
</ol>


## Usage
<ol type="1">
  <li>
    Open terminal, run: <!-- I hope the reference won't be too obvious -->

```
elford
```
  </li>
  <li>
    Alternatively, in a Python file (*.py), you can do:
    
```
from claire import main
main()
```
  </li>
</ol>

## Requirement(s)
1.  Python 3.x

## Note(s)
1. Deleting the config folder/file could cause everything to revert back to the default setting the next time you boot up the progam.
2. The program won't check any of the contents of any subfolders for simplicity sake, subfolders will be put into the "Others" folder. (Will probably add this as a switch if you guys want to)

## License
This project is licensed under the GNU General Public License 3.0, check [LICENSE](LICENSE) for more details.
