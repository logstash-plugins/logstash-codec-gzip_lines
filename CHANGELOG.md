## 3.0.4
 - Fixes issue where decode operation did not support string arguments [#3](https://github.com/logstash-plugins/logstash-codec-gzip_lines/issues/3)

## 3.0.3
  - Update gemspec summary

## 3.0.2
  - Fix some documentation issues

# 3.0.0
  - breaking: update to use new plugin api
# 2.0.4
  - Depend on logstash-core-plugin-api instead of logstash-core, removing the need to mass update plugins on major releases of logstash
# 2.0.3
  - New dependency requirements for logstash-core for the 5.0 release
## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully, 
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0

