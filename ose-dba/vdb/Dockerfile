FROM rhel7:latest

LABEL Name="jboss-datavirt-6/demo-jdv-extensions" \
      Version="latest" \
      Release="latest" \
      Architecture="x86_64" 

COPY injected-files /injected/injected-files
COPY injected-modules /injected/injected-modules
COPY install.sh /injected/install.sh
COPY install.properties /injected/install.properties

