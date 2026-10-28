testing :

url -s -X POST http://localhost:9696/predict -H "Content-Type: application/json" -d @json_data/json1.json

url -s -X POST http://localhost:9696/predict -H "Content-Type: application/json" -d @json_data/json2.json
