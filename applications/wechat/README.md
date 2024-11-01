# For new installations of OpenSearch 2.12 and later, you must define a custom admin password in order to set up a demo security configuration.
# Use one of the following commands to define a custom admin password:

## Install the x64 package using yum.
sudo env OPENSEARCH_INITIAL_ADMIN_PASSWORD=<custom-admin-password> yum install opensearch-2.17.1-linux-x64.rpm

## Install the x64 package using rpm.
sudo env OPENSEARCH_INITIAL_ADMIN_PASSWORD=<custom-admin-password> rpm -ivh opensearch-2.17.1-linux-x64.rpm

## Install the arm64 package using yum.
sudo env OPENSEARCH_INITIAL_ADMIN_PASSWORD=<custom-admin-password> yum install opensearch-2.17.1-linux-arm64.rpm

## Install the arm64 package using rpm.
sudo env OPENSEARCH_INITIAL_ADMIN_PASSWORD=<custom-admin-password> rpm -ivh opensearch-2.17.1-linux-arm64.rpm

# Use the following command for OpenSearch versions 2.11 and earlier:

## Install the x64 package using yum.
sudo yum install opensearch-2.17.1-linux-x64.rpm

## Install the x64 package using rpm.
sudo rpm -ivh opensearch-2.17.1-linux-x64.rpm

## Install the arm64 package using yum.
sudo yum install opensearch-2.17.1-linux-arm64.rpm

## Install the arm64 package using rpm.
sudo rpm -ivh opensearch-2.17.1-linux-arm64.rpm