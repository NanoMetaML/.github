<p align=center>
<picture><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Purdue_Boilermakers_logo.svg/1200px-Purdue_Boilermakers_logo.svg.png" alt="Purdue Logo" width=200></picture>
</p>
<h1 style="font-size:40px;" align=center>
NanoMetaML Team 
</h1>

Welcome to the NanoML (NanoMetaML) team's github repo! We are a team of researchers at Purdue University and Oak Ridge National Lab working on the intersection of quantum computing, nanophotonics, and machine learning.
Our team develops high quality machine learning code and we hope it is useful for your projects!
We focus on speeding up the characterization of materials in laboratory settings, generation of unique nanophotonic and quantum devices, and fast algorithms written in Rust, Python, C/C++.  

We take a first principles approach to develop new perspectives at the intersection of physics, computer science, and machine learning.

<h1 style="font-size:30px;" align=center>
Collaborations 
</h1>

<picture><img src="https://techcrunch.com/wp-content/uploads/2021/11/QuEra-Computing-Inc.-logo-black.png?w=300" alt="Purdue Logo" height=70></picture>
<picture><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Microsoft_logo_%282012%29.svg/512px-Microsoft_logo_%282012%29.svg.png" alt="Microsoft Logo" height=70></picture>
<picture><img src="https://www.ornl.gov/sites/default/files/styles/large/public/2020-08/QSCLogo_Color_H%5B1%5D.jpg" alt="Purdue Logo" height=70></picture>
<picture><img src="https://1000logos.net/wp-content/uploads/2017/02/Harvard-Logo.png" alt="Purdue Logo" height=70></picture>
<picture><img src="https://tnadvancedenergy.com/site/wp-content/uploads/2015/10/Logo_ORNL-1.png" alt="Purdue Logo" height=70></picture>

## Collaboration Policy

Our team is always looking for new opportunities for collaboration. If you are interested in starting a new project or collaborating on one of our ongoing research efforts, please reach out to Blake Wilson at wilso692@purdue.edu or Alexandra Boltasseva at aeb@purdue.edu.

<h1 style="font-size:30px;" align=center>
Team Languages 
</h1>

![Python](https://img.shields.io/badge/-Python-cfb991?logo=python&logoColor=white&style=for-the-badge)
![Cpp](https://img.shields.io/badge/-C++-cfb991?logo=cplusplus&logoColor=white&style=for-the-badge)
![C](https://img.shields.io/badge/-C-cfb991?logo=c&logoColor=white&style=for-the-badge)
![Rust](https://img.shields.io/badge/-Rust-cfb991?logo=rust&logoColor=white&style=for-the-badge)


We implement 3 pretty standard systems for managing our repos.

1. Virtual environments
2. Version Control
3. Packaging

Our goal is to make our code as easy as

    pip install our-package


## Why do we as academics care about good code?

Academia's goal is to further humanity's knowledge and provide access to education with as few hurdles as possible. By making our code easy to use, we bring academia's goal closer to reality and open doors for anyone to come into science. Virtual environments, version control, and proper packaging make our code easily accessible and give access closer to anyone.

### Version Control

Git helps us track changes in our code, collaborate with other team members, and manage releases. It also allows others to easily contribute to our projects and fork them for their own use.

### Virtual Environments

Virtual environments are essential for isolating project dependencies and avoiding conflicts between different Python packages. We use virtual environments to manage and install project-specific packages, ensuring a consistent and reproducible development environment for all contributors.

### Packaging

Packaging code is a widely used package management tool for Python. We use it to define, package, and distribute our code as reusable modules or libraries. This makes it easy for others to install and use our code without worrying about dependencies or compatibility issues.

# Installing Python Packages

To install any of our python packages, simply install directly from github using the following cli command:

        python -m pip install git+https://github.com/nanometaml/<git-repo-name>.git

### Why python -m? 
Good question! If you type in `pip` into the cmd, it's not guaranteed to be linked to the same python binary found on your cmd path. The only way to guarantee that the package is installed to the correct python, you have to run pip using python's module mode, i.e., 'python -m pip'.
If you see this message, everything is working properly!

### Optional

Become a collaborator on the NanoMetaML organization!!
Email Blake Wilson and Alexandra Boltasseva at wilso692@purdue.edu and aeb@purdue.edu for information on collaborating with our team.

# Contributing

We welcome contributions from the community! If you would like to contribute to our projects or start a collaboration with one of our gifted team members, please follow these steps:

1. Fork the repository.

2. Create a new branch for your changes.

3. Make your changes and commit them, making sure to follow our commit message guidelines.

4. Push your changes to your fork.

5. Create a pull request against our repository, describing your changes and any relevant information.

Our team will review your pull request and provide feedback or merge it if approved.

# License

All NanoML projects are released under the MIT License. This permissive license allows you to use, modify, and distribute our code, as long as you include the original copyright and license information.
