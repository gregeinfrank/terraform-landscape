# Terraform Landscape Change Log

## 0.1.9

* Fix handling of additional indentation in Terraform 0.10.0 output

## 0.1.8

* Fix handling of Terraform plan outputs when `-out` flag not specified

## 0.1.7

* Gracefully handle case where Terraform output does not contain postface

## 0.1.6

* Fix handling of read action resources (`<=`)

## 0.1.5

* Fix handling of Windows line endings

## 0.1.4

* Fix handling of repeated resources with index numbers
* Fix changing resource attributes from empty string to JSON
* Fix handling of consecutive resources with no attributes

## 0.1.3

* Fix handling of resources rebuilt due to attribute changes with
  `(forces new resource)` in output

## 0.1.2

* Fix handling of rebuilt/tainted resources

## 0.1.1

* Fix handling of resources with no attributes

## 0.1.0

* Don't require `-out` flag on Terraform command
* Fix handling of Terraform output with no changes

## 0.0.1

* Initial release
