FROM microsoft/mssql-server-linux
ARG ACCEPT_EULA
ARG MSSQL_PID
ARG SA_PASSWORD
ENV ACCEPT_EULA=$ACCEPT_EULA
ENV MSSQL_PID=$MSSQL_PID
ENV SA_PASSWORD=$SA_PASSWORD
RUN /opt/mssql/bin/sqlservr
