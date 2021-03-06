```python runnable
root = {}
root['Page']['Python']['defaultdict']['Title'] = 'Using defaultdict'
root['Page']['Python']['defaultdict']['Subtitle'] = 'Create a tree'
root['Page']['Java'] = None

print(json.dumps(root, indent=4))
```


### 跑出一個 Bash Terminal on the docker 
```python runnable
# {
# autofold
# Please ignore this part
print("TECHIO> terminal -i \"python3 main.py\"")
print("\033[2J")
# }
input('Press Enter')  # 一定要有個 input() 否則會馬上 stopped 啥事都不能做。
```

# Welcome to Python Project Template!

This Python template lets you get started quickly with a simple working example. If it is your first contribution then you should have a look at the [Getting Started](https://tech.io/doc/getting-started-create-playground) document.


The source code is on [GitHub](https://github.com/TechDotIO/python-template), please feel free to come up with proposals to improve it.

# Hands-on Demo

@[Luke, how many stars are there in these galaxies?]({"stubs": ["universe.py"], "command": "python3 test_universe.py"})

Check out the markdown file [`welcome.md`](https://github.com/TechDotIO/python-template/blob/master/markdowns/welcome.md) to see how this exercise is injected into the template.

# Template Resources

[`markdowns/welcome.md`](https://github.com/TechDotIO/python-template/blob/master/markdowns/welcome.md)
What you are reading here is generated by this file. Tech.io uses the [Markdown syntax](https://tech.io/doc/reference-markdowns) to render text, media and to inject programming exercises.


[`python-project`](https://github.com/TechDotIO/python-template/tree/master/python-project)
A simple Python project dedicated to run the programming exercise above. A project relies on a Docker image to run. You can find images on the [Docker Hub](https://hub.docker.com/explore/) or you can even [build your own](https://tech.io/doc/reference-runner).


[`techio.yml`](https://github.com/TechDotIO/python-template/blob/master/techio.yml)
This *mandatory* file describes both the table of content and the programming project(s). The file path should not be changed.


# Visual and Interactive Content

Tech.io provides all the tools to embed visual and interactive content like a Web app or a Unix terminal within your contribution. Please refer to the [documentation](https://tech.io/doc) to learn more about the viewer integrations.
