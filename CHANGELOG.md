# Change Log

## v4.0.0

### Breaking Changes

- v4.0.0 requires cspace-ui version 6. The record editor form for object records now uses the annotation fields that are defined in cspace-ui as of version 6, instead of using the (now deprecated) cspace-ui-plugin-ext-annotation plugin.

## v3.0.0

v3.0.0 Adds support for CollectionSpace 6.1.

### Breaking Changes

- A new field group, `annotationGroupList/annotationGroup`, has been added to the record editor form for object records. This field exists in the Fine and Contemporary Art profile in CollectionSpace 6.1, but not in prior versions of CollectionSpace. To use this version of cspace-ui-plugin-profile-fcart with an older version of the CollectionSpace server, this new field group should be hidden; otherwise, any values entered will not be saved.

## v2.1.0

- - Added the Named Collection field to the Object record editor form (only if using cspace-ui version 5).

## v2.0.0

v2.0.0 Adds support for CollectionSpace 6.0.

### Breaking Changes

- v2.0.0 requires cspace-ui version 4. If you've customized this profile, see the cspace-ui 4.0.0 change log for configuration changes that may be needed.
