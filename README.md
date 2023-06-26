# Kastro_qa_guru_poetry_dependency_management_hw18

poetry new -> Creates a new Python project at <path>.

poetry init -> Creates a basic pyproject.toml file in the current directory.

poetry add -> Adds a new dependency to pyproject.toml.

poetry add --group=dev plint==2.17.4 -> Adds a new dependency to group dev

poetry install --without=dev -> Adds a new dependencies but not from group dev

poetry env use 3.11 -> changes python version in the env

poetry exit -> to exit from env 

poetry list -> shows a command list
