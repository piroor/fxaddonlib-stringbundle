# String Bundle Utility

## Abstract

XUL's <stringbundle> has some useful methods, but nsIStringBundle doesn't.
This provides a wrapper for nsIStringBundle compatible to <stringbundle>.

## Usage

    var bundle = window['piro.sakura.ne.jp']
                          .stringBundle
                          .get('chrome://example/locale/example.properties');
    bundle.getString('key1');
    bundle.getFormattedString('key2', [val1, val2]);

