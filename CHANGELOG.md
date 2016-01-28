## 0.2.0 - 2016-01-26

* [new feature] Added mode parameters and support 4 modes(append, replace, replace_backup, delete_in_advance). [#20](https://github.com/embulk/embulk-output-bigquery/pull/20) [#21](https://github.com/embulk/embulk-output-bigquery/pull/21) @joker1007 thanks!

## 0.1.11 - 2015-11-16

* [maintenance] Change error result display for easy investigation. [#18](https://github.com/embulk/embulk-output-bigquery/pull/18)

## 0.1.10 - 2015-10-06

* [new feature] Added new auth method - json_keyfile of GCP(Google Cloud Platform)'s service account [#17](https://github.com/embulk/embulk-output-bigquery/pull/17)

## 0.1.9 - 2015-08-19

* [maintenance] Upgraded Embulk version to 0.7.1

## 0.1.8 - 2015-08-19

* [new feature] Supported mapreduce-executor. @frsyuki thanks! [#13](https://github.com/embulk/embulk-output-bigquery/pull/13)
* [maintenance] Fixed job_id generation logic [#15](https://github.com/embulk/embulk-output-bigquery/pull/15)
* [maintenance] Refactored [#11](https://github.com/embulk/embulk-output-bigquery/pull/11)

## 0.1.7 - 2015-05-20

* [new feature] Added allow_quoted_newlines option [#10](https://github.com/embulk/embulk-output-bigquery/pull/10)
* [maintenance] Upgraded embulk version to 0.6.8

## 0.1.6 - 2015-04-23

* [new feature] Added ignore_unknown_values option to job_id generation logic. [#9](https://github.com/embulk/embulk-output-bigquery/pull/9)

## 0.1.5 - 2015-04-23

* [new feature] Added ignore_unknown_values option.  [#8](https://github.com/embulk/embulk-output-bigquery/pull/8) @takus thanks!

## 0.1.4 - 2015-04-21

* [new feature] Added prevent_duplicate_insert option

## 0.1.3 - 2015-04-06

* [new feature] Added new auth method - pre-defined access token of GCE(Google Compute Engine)
* [maintenance] Updated Google provided libraries
  * http-client:google-http-client-jackson2 from 1.19.0 to 1.20.0
  * apis:google-api-services-bigquery from v2-rev193-1.19.1 to v2-rev205-1.20.0

## 0.1.2 - 2015-04-01

* [new feature] Changed bulk-load method from "via GCS" to direct-insert
* [new feature] added dynamic table creationg option