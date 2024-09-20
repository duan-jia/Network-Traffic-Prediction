FROM tensorflow/tensorflow:2.16.1-gpu-jupyter AS base

WORKDIR /app

COPY requirements.txt .

RUN <<EOF
apt-get update
EOF

RUN pip install --no-cache-dir -r requirements.txt

