docker-compose build
docker-compose up
docker run -i -t -p 9091:9091 jupyter-lab /bin/bash -c "/opt/conda/bin/jupyter lab --notebook-dir=/opt/notebooks --ip="*" --port=9091 --no-browser --allow-root"