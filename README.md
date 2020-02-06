# orion-alert-to-hec

* master: [![Build Status - master](https://travis-ci.com/djschaap/kv-to-json-sandbox.svg?branch=master)](https://travis-ci.com/djschaap/kv-to-json-sandbox)
* go: [![Build Status - go](https://travis-ci.com/djschaap/kv-to-json-sandbox.svg?branch=go)](https://travis-ci.com/djschaap/kv-to-json-sandbox)

## Overview

orion-alert-to-hec reads messages from an AWS SQS queue, reformats them,
and submits them to Splunk HTTP Event Collector (HEC).
