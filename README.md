# DeepReferencer

Utility module to index all references and attributes available from any Entity in your domain model. Provides a quick way to access all values within your application. Also indexes access rules so you can implement those in other modules that directly work with the available data.

### Dependencies:
- MxModelReflection
- CommunityCommons

## Usage
1. Add Admin role to your administrator role
2. Add ReferenceEntity_Overview to navigation
3. Add any Entities you want to index
4. Use "Find all attributes" to index all possible references up to 2 deep or add references to be used manually

## Known issues
- Find all attributes only finds unique references to every related object
- Names only show what object and attribute they refer to, not the path used to get there
