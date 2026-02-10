# Fork Changes Documentation

This document tracks all custom modifications, patches, and deviations from the upstream `robert-luoqing/flutter_list_view` repository.

## Fork Information

- **Fork Repository**: `https://github.com/pieces-app/flutter_list_view`
- **Upstream Repository**: `https://github.com/robert-luoqing/flutter_list_view`
- **Current Branch**: `master`
- **Fork Version**: `1.1.29`
- **Commits Ahead**: 1
- **Commits Behind**: 0
- **Last Upstream Merge**: Fork is fully caught up with upstream

## Custom Modifications

### 1. Padding Support
- **Commit**: `4592697`
- **Changes**:
  - Added padding support to `FlutterListView` widget
- **Reason**: Needed configurable padding for list views in Pieces UI layouts

## Upstream Sync Status

- **Current Gap**: 0 commits behind (fully synced)
- **Status**: Only 1 custom commit diverging from upstream

## Why This Fork Exists

1. **Padding Support**: Upstream `FlutterListView` does not support configurable padding

## Future Considerations

1. **Upstream Contribution**: The padding support is a clean, minimal addition that could easily be contributed upstream
2. **Consider Dropping Fork**: If upstream accepts the padding PR, the fork can be dropped
3. **Monitor Upstream**: Check branches `add_children_to_subsliver`, `fix-null-issue`, `refactor_new_height_manager` for upstream improvements

## Contact

For questions about this fork or to request changes, contact the Pieces development team.
