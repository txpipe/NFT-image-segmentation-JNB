Follow below instructions to setup dependencies :
1.Create virtual environment
   Once boilerplate is downloaded cd into the semantic-segmentation-boilerplate folder and execute below commands
   For unix/macOS:
      -sudo apt-get install python3-venv
      -sudo python3 -m venv venv
      -source ./venv/bin/activate
   For Windows:
      -py -m pip install --user virtualenv
      -py -m venv venv
      -.\venv\Scripts\activate
2.Run following command to install dependencies
   - pip install -r requirement.txt
3.Replace appropriate values in config.py, service.py and run below command to invoke service   - python service.py