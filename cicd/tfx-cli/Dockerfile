FROM tensorflow/tfx:0.15.0rc0
RUN RELEASE=0.1.32 \
&& pip install https://storage.googleapis.com/ml-pipeline/release/$RELEASE/kfp.tar.gz

ENV LC_ALL=C.UTF-8 LANG=C.UTF-8

ENTRYPOINT ["tfx"]
