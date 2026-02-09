# stockagent - how-to
- Download the two Ampere optimized models from Huggingface:  llama-3.1-8b-instruct-Q8R16.gguf and Llama-3.2-3B-Instruct-Q4_K_4.gguf
- Place the two models inside the models directory.
- Run 'start_app.sh'.  The script will pull the demo docker image from docker hub, setup the environments neccessary for this demo.
- When the docker container is up running (by checking:  'docker ps' command), access to its container.  At the prompt, run "python3 server.py".  It will start the frontend UI.
- Open the demo at http:<your ip address>:5000

    
