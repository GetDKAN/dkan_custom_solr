# dkan_custom_solr
DKAN is shipped with a search powered by the database, though it can be used in production environments using a Solr server. By enabling this module, you'll be able to use a Solr server in local development.

This module provides the settings for creating a local development Solr server using [DKAN Tools](https://github.com/GetDKAN/dkan-tools) and will update the datasets and groups search indexes provided by DKAN.

Note: this server will be created using settings based on the [DKAN Tools](https://github.com/GetDKAN/dkan-tools) Solr container, if you are not using DKAN Tools, you'll still be able to use this module but may need to update the respective configuration in `admin/config/search/search_api/server/dkan_custom_solr/edit`.

If you want to stop using the local Solr server provided by this module, simply disable this module and revert the indexes to their original config in `admin/config/search/search_api`.
