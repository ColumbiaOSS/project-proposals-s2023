*Conda* currently has limited options to export an environment. Most people export an envrionment by saving every single package.

Instead, I want to add the functionality of [Conda Minify](https://github.com/jamespreed/conda-minify), an external library, to Conda itself. This library finds the "minimum requirements needed to approximately reproduce the environment. Conda can figure out the rest of the details for the dependencies. For example, if you have an environment with Pandas and Matplotib; sharing the environment really only requires specifying Pandas and Matplotib and their versions."

