# Release Notes

## Next Release

* fixed the nuget package names - now using XMLUnit.Core and
  XMLUnit.Constraints
* The XMLUnit.Constraints nuget package now depends on NUNit 2.6.4 -
  which it has been compiled against - rather than 2.5.10.
* added new overloads to `IXPathEngine`
* fixed the XPath context used by the `ByXPath` element selector so
  that "." now refers to the current element.
  Issue [xmlunit/#39](https://github.com/xmlunit/xmlunit/issues/39)

## XMLUnit.NET 2.0.0-alpha-02 - /Released 2015-11-21/

This is the initial alpha release of XMLUnit.NET.  We expect the API
to change for the next release based on user feedback.
