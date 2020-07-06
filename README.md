# String Bundle Utility, for Firefox older than its version 57.

This project is obsolete and not maintained anymore.

## Abstract

XUL's "stringbundle" element has some useful methods, but nsIStringBundle doesn't.
This provides a wrapper for nsIStringBundle compatible to "stringbundle".

## Usage

    var bundle = window['piro.sakura.ne.jp']
                          .stringBundle
                          .get('chrome://example/locale/example.properties');
    bundle.getString('key1');
    bundle.getFormattedString('key2', [val1, val2]);

