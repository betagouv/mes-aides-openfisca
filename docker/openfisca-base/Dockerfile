FROM python:2.7-slim

# We purposely install NumPy & SciPy via package manager, for faster builds
RUN apt-get update && apt-get install -y --no-install-recommends \
    gcc \
    python-dev \
    git \
    libyaml-dev \
    libyaml-dev \
    python-numpy \
    python-scipy

# RUN mkdir /usr/src/openfisca
# WORKDIR /usr/src/openfisca

# COPY api.py ./
# COPY config.py ./
# COPY requirements.txt ./

# RUN pip install --upgrade -r requirements.txt

# COPY docker-entrypoint.sh /

# RUN chmod +x /docker-entrypoint.sh

# ENTRYPOINT ["/docker-entrypoint.sh"]
