## OpenMoney Gift interface for openmoney-gift-api

The OpenMoney Gift API is a variant of the [OpenMoney API]https://github.com/jethro-swan/openmoney-api/ 
for use with the [OpenMoney Gift]https://github.com/jethro-swan/openmoney-gift/ interface.

### Install (e.g. locally or in headless VM)

Copy  openmoney-gift-nginx.conf.example  to  openmoney-gift-nginx.conf  and edit if necessary.


```sh
git clone https://github.com/jethro-swan/openmoney-gift-api
cd openmoney-gift
npm install
./install.sh <email from which alterts/response are sent> <URL of site>
```

### Run in a background service

If not already installed
```sh
sudo npm install pm2 -g
```

Start application
```sh
pm2 start app.js --name "openmoney-gift-api"
```

### License

Copyright [2019] [Dominique Legault]

Minor revisions:

  2019/11/03 John Waters
  
  2019/11/05 John Waters
  
  2020/03/12 John Waters

  
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.