# proactive-tasks

Repository setup:

```
git submodule add https://github.com/ow2-proactive/proactive-examples.git ./submodules/proactive-examples

ln -s ./submodules/proactive-examples/MachineLearningScripts/resources/catalog ./machine_learning_scripts
ln -s ./submodules/proactive-examples/DeepLearningScripts/resources/catalog ./deep_learning_scripts

ln -s ./submodules/proactive-examples/MachineLearningScripts/METADATA.json machine_learning_scripts.json
ln -s ./submodules/proactive-examples/DeepLearningScripts/METADATA.json deep_learning_scripts.json
```
