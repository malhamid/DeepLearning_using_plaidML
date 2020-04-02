# DeepLearning using plaidML
DeepLearing using PlaidML

## Installing PlainML
You can refer to the installation guide on PlaidML offical Github repristory git remote add origin https://github.com/malhamid/DeepLearning_using_plaidML.git

I have tried to install PlainML on MacOS machine using only the following commands: 
- We need to install virtualenv using 
```pip install virtualenv```
- We need to create a new environment:
```python -m venv myenv```
- Activate the new virtual environemnt: 
```source myenv/bin/activate```
- Installing PlaidML for Keras
```pip install -U plaidml-keras```
- Now we have to tell plaidml to use our computer resources
```plaidml-setup```
  During the setup, you would be asked three questions, make sure if you are using MacOS to choose AMD option for the last question. 
  
That's all what you need.
Good luck
