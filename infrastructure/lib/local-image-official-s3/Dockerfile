# Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
# SPDX-License-Identifier: MIT-0
FROM osimis/orthanc:23.4.0 as release

# Create non-root Orthanc user and group
RUN groupadd -r orthanc -g 433 && \
    useradd -u 431 -r -g orthanc -c "Orthanc user" orthanc
RUN chmod -R 755 /usr/share/orthanc
RUN chown -R orthanc /usr/share/orthanc
#USER orthanc

