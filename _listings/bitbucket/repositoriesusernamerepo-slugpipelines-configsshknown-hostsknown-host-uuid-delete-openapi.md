---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Delete Repositories Username Repo Slug Pipelines Config Ssh Known
    Hosts Known Host Uu
  description: Delete repositories username repo slug pipelines config ssh known hosts
    known host uu
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pipelines_config/ssh/known_hosts/:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
      description: Get repositories username repo slug pipelines config ssh known
        hosts
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHosts
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hosts-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Ssh
      - Known
      - Hosts
    post:
      summary: Add Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
      description: Post repositories username repo slug pipelines config ssh known
        hosts
      operationId: postRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHosts
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hosts-post
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The known host to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Ssh
      - Known
      - Hosts
  /repositories/{username}/{repo_slug}/pipelines_config/ssh/known_hosts/{known_host_uuid}:
    delete:
      summary: Delete Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
        Known Host Uu
      description: Delete repositories username repo slug pipelines config ssh known
        hosts known host uu
      operationId: deleteRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hostsknown-host-uuid-delete
      parameters:
      - in: path
        name: known_host_uuid
        description: The UUID of the known host to delete
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Ssh
      - Known
      - Hosts
      - Known
      - Host
      - Uu
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---