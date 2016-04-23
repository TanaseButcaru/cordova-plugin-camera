# 2.2.0-unofficial-1

Release notes:
 
 * [27cb493](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/27cb493b6ded34c623fb5c7615b52e51ed632700) Sync to upstream/master.

# 2.1.1-unofficial-1 / 2

Release notes:
 
 * [7ed1e4c](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/7ed1e4cd49c6b43604e32c3fad1bb8653f068be3) Sync to upstream/master.

Note: changes made to ``FileHelper`` are not equal or even better than filepath port implementation (missing cases); keeping the filepath implementation.

# 2.1.0-unofficial-4 / 5

Bump version number for npmjs.

# 2.1.0-unofficial-3

Release notes:

 * [0bb178b](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/0bb178bbcc722b54a8a4d48f4a0621cbe7767e10): The user get what he wants! When destination type is ``FILE_URI`` the success callback will return a ``file://`` path, otherwise, ``NATIVE_URI``, will return a ``content://`` uri.
 * [5fc9a55](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/5fc9a559933bf034dd712fa70c8514689d62c6a9): Port [cordova-plugin-filepath-unofficial](https://github.com/TanaseButcaru/cordova-plugin-filepath-unofficial) and replace ``FileHelper``'s ``getRealPath`` with it. This resolves a lot of bugs.
 * Revert all commits that were fixing problems with file paths (for both pictures & videos).


# 2.1.0-unofficial-2

Release notes:

 * Sync with upstream/master.
 * [e032811](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/e032811c1cf2b382f8576d92cb04e41e0193e221): Prevent empty video fileLocation in case ``getRealPath`` returns an empty string. Now returning the ``content://`` uri scheme.
 * [026a48d](https://github.com/TanaseButcaru/cordova-plugin-camera-unofficial/commit/026a48dd08649b11ed2910cb58d223ed7078d483): CB-10270 android: Added back support for file:// URIs to getRealPath


# 2.1.0-unofficial-1

Initial unofficial release.
