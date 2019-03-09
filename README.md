# Keras Adversarial 101

    nvidia-docker run --rm -it \
        -v $PWD:/notebooks \
        -e PASSWORD='pass' \
        -e NVIDIA_VISIBLE_DEVICES='0' \
        -p 8888:8888 tensorflow/tensorflow:1.12.0-gpu-py3