FROM python:3.9-alpine3.12

LABEL IMAGE="example-extract-study-id"
LABEL VERSION="0.1.0"
LABEL CI_IGNORE="True"

RUN pip3 install pydicom==2.0.0

COPY files/extract_study_id.py /

CMD ["python3","-u","/extract_study_id.py"]