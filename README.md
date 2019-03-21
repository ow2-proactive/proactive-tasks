# proactive-tasks

Repository clone:

```
git clone --recursive https://github.com/ow2-proactive/proactive-tasks.git
```

Repository setup:

```
git submodule add https://github.com/ow2-proactive/proactive-examples.git ./submodules/proactive-examples

# folders
ln -s ./submodules/proactive-examples/MachineLearning/resources/catalog ./machine_learning_tasks
ln -s ./submodules/proactive-examples/MachineLearningScripts/resources/catalog ./machine_learning_scripts
ln -s ./submodules/proactive-examples/DeepLearning/resources/catalog ./deep_learning_tasks
ln -s ./submodules/proactive-examples/DeepLearningScripts/resources/catalog ./deep_learning_scripts

# metadata files
ln -s ./submodules/proactive-examples/MachineLearning/METADATA.json machine_learning_tasks.json
ln -s ./submodules/proactive-examples/MachineLearningScripts/METADATA.json machine_learning_scripts.json
ln -s ./submodules/proactive-examples/DeepLearning/METADATA.json deep_learning_tasks.json
ln -s ./submodules/proactive-examples/DeepLearningScripts/METADATA.json deep_learning_scripts.json
```
