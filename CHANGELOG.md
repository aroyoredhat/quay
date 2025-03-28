## Red Hat Quay Release Notes

[Red Hat Customer Portal](https://access.redhat.com/documentation/en-us/red_hat_quay/3.7/html/red_hat_quay_release_notes/index)


<a name="v3.9.11"></a>
## v3.9.11 - 2025-03-26
### .Github/Actions
- [1cad9081](https://github.com/quay/quay/commit/1cad9081189a591bea209c7929af750dc64de49d): only run dependabot changes on PR ([#360](https://github.com/quay/quay/issues/360))
### API
- [2dca65f9](https://github.com/quay/quay/commit/2dca65f9cef56581457535b70683ec93bcde2876): Removing internal only decorator from exposed Super user endpoints ([#1271](https://github.com/quay/quay/issues/1271))
### API/UI
- [5c342969](https://github.com/quay/quay/commit/5c342969203e28124818407a97cf078aba6a47f6): Filtering of tags API through query parameter (PROJQUAY-5362) ([#1839](https://github.com/quay/quay/issues/1839))
### Api
- [6b07d728](https://github.com/quay/quay/commit/6b07d7282ba77e9ae0f394073dfa2a6af1ca77a1): accepting empty body for create robot endpoints (PROJQUAY-6224) ([#3682](https://github.com/quay/quay/issues/3682))
- [b911d480](https://github.com/quay/quay/commit/b911d480cf801dbef929338f8458ee38c9780b78): allow manifests to be pulled by digest (PROJQUAY-5467) ([#1877](https://github.com/quay/quay/issues/1877))
- [84abdba0](https://github.com/quay/quay/commit/84abdba07616ffabb2afb42673ec0bf2cf5badd0): Allow setting multiple CORS_ORIGIN (PROJQUAY-5213) ([#1791](https://github.com/quay/quay/issues/1791))
- [2b3c3cc5](https://github.com/quay/quay/commit/2b3c3cc58482b94e83ad4b5483a5a4de7bdee6b4): feature to limit org creation to superusers (PROJQUAY-1245) ([#1516](https://github.com/quay/quay/issues/1516))
- [aefddd36](https://github.com/quay/quay/commit/aefddd36dd0540709f391a86485a8afb2a57e85a): add OPTIONS method to /config request (PROJQUAY-4276) ([#1476](https://github.com/quay/quay/issues/1476))
- [d37dd766](https://github.com/quay/quay/commit/d37dd766accdaa8c2af5c465af2fd6f2948ed990): fix CORS headers, use concat instead of extend (PROJQUAY-4163) ([#1445](https://github.com/quay/quay/issues/1445))
- [871c43ea](https://github.com/quay/quay/commit/871c43eaf37ea44da13308e06b2e2f9c543fc5dd): handle missing tag on DELETE tag api ([#1444](https://github.com/quay/quay/issues/1444))
- [bf99e718](https://github.com/quay/quay/commit/bf99e718513b41e67ee2963e220d93e59e4acac5): Update werkzeug to 1.0.0 and add valid CORS methods (PROJQUAY-4163) ([#1443](https://github.com/quay/quay/issues/1443))
- [896a3aab](https://github.com/quay/quay/commit/896a3aab3a8109cf2e8899aadd865d4d77927719): update the quota api so that it's more consistent with the other apis endpoints (PROJQUAY-2936) ([#1221](https://github.com/quay/quay/issues/1221))
- [02dfc63f](https://github.com/quay/quay/commit/02dfc63f42eff253571fbe6da8d48adf48660202): fully deprecate image api endpoints (PROJQUAY-3418) ([#1164](https://github.com/quay/quay/issues/1164))
- [6470248b](https://github.com/quay/quay/commit/6470248be1ca55ab3ea6f2a364bc02547976186d): /v1/user/initialize to create first user (PROJQUAY-1926) ([#771](https://github.com/quay/quay/issues/771))
### App.Py
- [b4600553](https://github.com/quay/quay/commit/b4600553b9327032149a52c5efc58a9da3e99ee7): filter proxy cache login details from debug logs ([#1268](https://github.com/quay/quay/issues/1268))
### Arch
- [434c193b](https://github.com/quay/quay/commit/434c193b9408367fe1800f7e9a01e92ef59a6e86): Map aarch64 to arm64 in ARCH variable ([#1602](https://github.com/quay/quay/issues/1602))
- [d08298bc](https://github.com/quay/quay/commit/d08298bc60858ac6b2c07387116f03d439188d31): add ppc64le support to quay (PROJQUAY-4595) ([#1535](https://github.com/quay/quay/issues/1535))
### Auth
- [d34e9399](https://github.com/quay/quay/commit/d34e9399af9e02f4beb7ed59cc8ff7124ecfece2): Adding wraps to user namespace decorator (PROJQUAY-4694) ([#1607](https://github.com/quay/quay/issues/1607))
- [ea90cc4f](https://github.com/quay/quay/commit/ea90cc4f26a625f4d228dae9cd362be8c0cc9ce9): Speed up permissions loading (PROJQUAY-4004) ([#1566](https://github.com/quay/quay/issues/1566))
- [6ed0bcde](https://github.com/quay/quay/commit/6ed0bcdedc9a0cb4a84197006602ba39c7f965ec): allow rs384 in jwt (PROJQUAY-4148) ([#1449](https://github.com/quay/quay/issues/1449))
- [6effd4cd](https://github.com/quay/quay/commit/6effd4cdec250bedb9a36b810dfec3519b61ed7b): Add state to the oauthorize redirect (PROJQUAY-3648) ([#1301](https://github.com/quay/quay/issues/1301))
- [edb4e721](https://github.com/quay/quay/commit/edb4e72166cb1c557dfcad27533226fa75827f9b): Add state to the oauthorize page (PROJQUAY-3648) ([#1292](https://github.com/quay/quay/issues/1292))
- [2219d5ae](https://github.com/quay/quay/commit/2219d5aed22f28546df28fac4a4c7d0cc783f9d6): Add state to the Oauth code response (PROJQUAY-3139) ([#1124](https://github.com/quay/quay/issues/1124))
- [0033f9b8](https://github.com/quay/quay/commit/0033f9b851502bd474d8ddd3faf4e5d78f43f9ca): Fix oauth code flow (PROJQUAY-781) ([#1044](https://github.com/quay/quay/issues/1044))
### Azure
- [63ed3d95](https://github.com/quay/quay/commit/63ed3d95399a32d511001b71042b74b469b6cf63): Remove parsing of error response (PROJQUAY-3718) ([#167](https://github.com/quay/quay/issues/167))
### Billing
- [2d949b3b](https://github.com/quay/quay/commit/2d949b3b2e5ac76c1415350cb908a942e89b85c4): allow changing subscription on empty stripe_id (PROJQUAY-5413) ([#1857](https://github.com/quay/quay/issues/1857))
- [e7a7b4a0](https://github.com/quay/quay/commit/e7a7b4a05003ed59f4ae7e1c5df9265d31a6b822): fallback to cards api if paymentmethod is not set (PROJQUAY-5129) ([#1826](https://github.com/quay/quay/issues/1826))
- [89725309](https://github.com/quay/quay/commit/89725309be8f73c5041513bd2d70adb5db4a24d7): update Stripe checkout to support 3DS (PROJQUAY-5129) ([#1818](https://github.com/quay/quay/issues/1818))
- [d05c32b9](https://github.com/quay/quay/commit/d05c32b9d11fd268b86198e2c62cc19179649f0a): update default subscription payment behavior ([#1778](https://github.com/quay/quay/issues/1778))
- [78896aa0](https://github.com/quay/quay/commit/78896aa0ceaa244e41988f5991c677a29e4ce263): fix new private repo count (PROJQUAY-4208) ([#1463](https://github.com/quay/quay/issues/1463))
- [17778979](https://github.com/quay/quay/commit/177789798139779d6e46032f595ddc2adfcbaf0f): add new larger stripe plan (PROJQUAY-4208) ([#1462](https://github.com/quay/quay/issues/1462))
- [8da53e97](https://github.com/quay/quay/commit/8da53e972047cec9a4339189112fe9b9272e3bb8): use BytesIO when rendering invoice (PROJQUAY-3267) ([#1174](https://github.com/quay/quay/issues/1174))
- [259da89c](https://github.com/quay/quay/commit/259da89cb64c85166f7bcd4b13ef007934e4c032): Remove type hints for FakeStripe (PROJQUAY-2777) ([#974](https://github.com/quay/quay/issues/974))
- [8d0aa9ff](https://github.com/quay/quay/commit/8d0aa9ffedb7d8148e890badf5c0bd86f4ef6e40): Remove annotations for type hints in billing (PROJQUAY-2777) ([#973](https://github.com/quay/quay/issues/973))
### Blobuploadcleanupworker
- [f35f3f13](https://github.com/quay/quay/commit/f35f3f137cd5d1e4594438e0db5c498651f1a396): Add BLOBUPLOAD_DELETION_DATE_THRESHOLD (PROJQUAY-2915) ([#1022](https://github.com/quay/quay/issues/1022))
- [22282dae](https://github.com/quay/quay/commit/22282dae093fc8f8bee543b1fa33e7f3c9c6b618): Add cleanup for orphaned blobs (PROJQUAY-2313) ([#967](https://github.com/quay/quay/issues/967))
### Bug
- [ee5ff714](https://github.com/quay/quay/commit/ee5ff7141f1096a2d6c79020df23791c8cd64e8a): Increase column size in logentry3 table (PROJQUAY-4305) ([#1510](https://github.com/quay/quay/issues/1510))
- [9209cf75](https://github.com/quay/quay/commit/9209cf7596d21719d4797c0caf8677cbc2347a1f): Fix schema discovery on basic auth (PROJQUAY-4362) ([#1498](https://github.com/quay/quay/issues/1498))
### Build
- [47141afc](https://github.com/quay/quay/commit/47141afc83a511bbd103aca82109071153d14687): disable push to backup repo for quayio-frontend (PROJQUAY-5229) ([#1834](https://github.com/quay/quay/issues/1834))
- [b7d95a18](https://github.com/quay/quay/commit/b7d95a180a56f08064b1662b6c5c30f4a07673cd): Add template for deploying quayio frontend in console (PROJQUAY-5229) ([#1835](https://github.com/quay/quay/issues/1835))
- [05e3773b](https://github.com/quay/quay/commit/05e3773b741289111d2590d0f1d909fd23c38166): Add build scripts for quay.io frontend (PROJQUAY-5229) ([#1833](https://github.com/quay/quay/issues/1833))
- [443b8d50](https://github.com/quay/quay/commit/443b8d50a9300a850473457deedc45c942116ebd): Update pyrsistent to fix Dockerfile.deploy (PROJQUAY-3125) ([#1079](https://github.com/quay/quay/issues/1079))
- [fba69d93](https://github.com/quay/quay/commit/fba69d939ec336c5fc46a9e5f5cfd9ee3b2ee38e): Add required setup.cfg for downstream build (PROJQUAY-2713) ([#946](https://github.com/quay/quay/issues/946)) ([#993](https://github.com/quay/quay/issues/993))
- [eb668cad](https://github.com/quay/quay/commit/eb668cad6622cc902bf1b88506dc0a8fc6d9f921): Use a configtool tag in the Dockerfile instead of master (PROJQUAY-2777) ([#972](https://github.com/quay/quay/issues/972))
- [78f8081a](https://github.com/quay/quay/commit/78f8081a0a53dd07096adc2545c9254112df3921): Use a configtool tag in the Dockerfile instead of master (PROJQUAY-2777) ([#971](https://github.com/quay/quay/issues/971))
- [a347d316](https://github.com/quay/quay/commit/a347d3167dece3078a119203137bf4230f8c01e5): Update backup base image name (PROJQUAY-2372) ([#965](https://github.com/quay/quay/issues/965))
- [d2f4efd8](https://github.com/quay/quay/commit/d2f4efd8428c6d7da6fd3038eaff6c15d57b05a1): Remove the image archive in post-deploy  (PROJQUAY-2372) ([#963](https://github.com/quay/quay/issues/963))
- [af2eeaa6](https://github.com/quay/quay/commit/af2eeaa61770adf69011369bb2efc86d3878165b): Use docker-archive for post-deploy script  (PROJQUAY-2372) ([#962](https://github.com/quay/quay/issues/962))
- [e8cf6339](https://github.com/quay/quay/commit/e8cf6339c31e76df608cab074f5acc3ee5f12095): Add docker-save to push images via skopeo on rhel-8 (PROJQUAY-2372) ([#960](https://github.com/quay/quay/issues/960))
- [d8b0e949](https://github.com/quay/quay/commit/d8b0e949005e6f78dd1368a55c578ac1fecc6091): Add docker-save to push images via skopeo on rhel-8 (PROJQUAY-2372) ([#959](https://github.com/quay/quay/issues/959))
- [759a83fa](https://github.com/quay/quay/commit/759a83fabfd64ec18554120fe74718599727fcd3): use Dockerfile for building quay app-sre (PROJQUAY-2373) ([#926](https://github.com/quay/quay/issues/926))
- [4c09559c](https://github.com/quay/quay/commit/4c09559cee9b68493483c6c7b8486afde64c6702): add full python build dependencies (PROJQUAY-2216) ([#822](https://github.com/quay/quay/issues/822))
- [1d63cfa2](https://github.com/quay/quay/commit/1d63cfa255d32c9eece8041452f13d78daab6e1a): update package-lock.json (PROJQUAY-1749) ([#821](https://github.com/quay/quay/issues/821))
- [9c8e3f1f](https://github.com/quay/quay/commit/9c8e3f1f486840513a65197dccdb77585f42c815): remove unused node modules (PROJQUAY-1667) ([#805](https://github.com/quay/quay/issues/805))
- [62e3bd9c](https://github.com/quay/quay/commit/62e3bd9cc7ca743ac472e6ae7f8099ba28a91fd5): update python pillow version (PROJQUAY-1520) ([#809](https://github.com/quay/quay/issues/809))
- [653dc021](https://github.com/quay/quay/commit/653dc021fea6358f8a56c344ade4e775605df15d): update node url-parse to 1.4.3 (PROJQUAY-1749) ([#797](https://github.com/quay/quay/issues/797))
### Build(Deps)
- [384aa6e5](https://github.com/quay/quay/commit/384aa6e5df2af3ca4fd46b8f7243ca167676716a): bump urllib3 from 1.26.9 to 1.26.18 (PROJQUAY-6110) ([#2458](https://github.com/quay/quay/issues/2458))
- [ef2035c7](https://github.com/quay/quay/commit/ef2035c7489649542374ecc4792139ed9745f7f0): bump golang.org/x/net from 0.13.0 to 0.17.0 (PROJQUAY-6208) ([#2435](https://github.com/quay/quay/issues/2435))
- [7d19eac7](https://github.com/quay/quay/commit/7d19eac7a0bdfb649f2be1f7de29f9e0d723d86b): bump certifi from 2022.12.7 to 2023.7.22 ([#2062](https://github.com/quay/quay/issues/2062))
- [d3b05d4b](https://github.com/quay/quay/commit/d3b05d4b8757fab82321e57db4065c682e0d0cda): bump reportlab from 3.5.55 to 3.6.13 (PROJQUAY-5691) ([#2056](https://github.com/quay/quay/issues/2056))
- [f8146c2d](https://github.com/quay/quay/commit/f8146c2de847254bae690de9d3e099006142fbed): bump config-tool to v0.1.21 ([#2051](https://github.com/quay/quay/issues/2051)) ([#2057](https://github.com/quay/quay/issues/2057))
- [f0e97152](https://github.com/quay/quay/commit/f0e97152cde66cf4f6b02ba189d081545c0f8a5c): bump pypdf2 from 1.27.6 to 1.27.9 ([#2052](https://github.com/quay/quay/issues/2052))
- [3791ff6a](https://github.com/quay/quay/commit/3791ff6a559389eec5c26584c4a82e44a10029af): bump decode-uri-component in /pkg/lib/editor ([#192](https://github.com/quay/quay/issues/192))
- [debc5b4e](https://github.com/quay/quay/commit/debc5b4e3fbfd1803123559063fd52ac7e8cd743): bump requests from 2.27.1 to 2.31.0 ([#1985](https://github.com/quay/quay/issues/1985))
- [3b1c7dba](https://github.com/quay/quay/commit/3b1c7dba22de00226fc07801625ff0f718fa1a59): bump socket.io-parser in /pkg/lib/editor ([#213](https://github.com/quay/quay/issues/213))
- [7c252e50](https://github.com/quay/quay/commit/7c252e50c34d2865461771932712f886199c3f69): bump minimist and karma in /pkg/lib/editor ([#210](https://github.com/quay/quay/issues/210))
- [117c5a86](https://github.com/quay/quay/commit/117c5a86065608e7a819454181d4c6ab9d3fc5d0): bump dns-packet from 5.3.1 to 5.4.0 in /web ([#1771](https://github.com/quay/quay/issues/1771))
- [a4384dbd](https://github.com/quay/quay/commit/a4384dbd8640ae76d9c877f18fb0e217c4830584): bump decode-uri-component from 0.2.0 to 0.2.2 in /web ([#1684](https://github.com/quay/quay/issues/1684))
- [4455df84](https://github.com/quay/quay/commit/4455df84440fd1b71a3a4f663d867fed14387ff7): bump loader-utils from 1.4.0 to 1.4.2 in /web ([#1685](https://github.com/quay/quay/issues/1685))
- [44363562](https://github.com/quay/quay/commit/443635629e1d34487afb746c2d5dcd99e16a79d7): bump json5 from 1.0.1 to 1.0.2 in /web ([#1699](https://github.com/quay/quay/issues/1699))
- [774efe37](https://github.com/quay/quay/commit/774efe37657ae804e325a4f6ea0bd27e36aa763e): bump oauthlib from 3.2.1 to 3.2.2 ([#1738](https://github.com/quay/quay/issues/1738))
- [50b14fe8](https://github.com/quay/quay/commit/50b14fe8278c829f3a1df7494a3fd333162b9dca): bump pillow from 9.0.1 to 9.3.0 ([#1633](https://github.com/quay/quay/issues/1633))
- [f42497f9](https://github.com/quay/quay/commit/f42497f95f8e666bb3276434ee131114f922db93): reduce CVEs in dependencies and runtime environment (PROJQUAY-4777) ([#1644](https://github.com/quay/quay/issues/1644))
- [972cab14](https://github.com/quay/quay/commit/972cab147bfcc763be1106c69cfde771b8e663eb): bump certifi from 2019.11.28 to 2022.12.7 ([#1665](https://github.com/quay/quay/issues/1665))
- [70473f00](https://github.com/quay/quay/commit/70473f000b8f93acd3c15a0cde6dd2a837a4fc3f): bump wheel from 0.35.1 to 0.38.1 ([#1690](https://github.com/quay/quay/issues/1690))
- [0dd53edf](https://github.com/quay/quay/commit/0dd53edf15ea7bfb836255be12b8ba1e0ce9f6f3): bump setuptools from 63.4.0 to 65.5.1 ([#1691](https://github.com/quay/quay/issues/1691))
- [42f46c93](https://github.com/quay/quay/commit/42f46c93c12453bd34ceff3de26c5cf23518d1da): bump express from 4.17.1 to 4.18.2 ([#1664](https://github.com/quay/quay/issues/1664))
- [6473166d](https://github.com/quay/quay/commit/6473166d0e9ab498977c99caa2ad8f9926dffcc5): bump decode-uri-component from 0.2.0 to 0.2.2 ([#1656](https://github.com/quay/quay/issues/1656))
- [d9352f0e](https://github.com/quay/quay/commit/d9352f0e9f80b1394b61dfe55e3218ac211b1f2f): bump protobuf from 3.15.0 to 3.18.3 ([#1541](https://github.com/quay/quay/issues/1541))
- [9a1de19f](https://github.com/quay/quay/commit/9a1de19f975800e2a4bbe384d87b8ceab416aa7e): bump angular and [@types](https://github.com/types)/angular ([#1451](https://github.com/quay/quay/issues/1451))
- [0c62c0ee](https://github.com/quay/quay/commit/0c62c0ee02920408fc8fa57b3580fef48a9d4ccf): bump terser from 4.3.4 to 4.8.1 ([#1452](https://github.com/quay/quay/issues/1452))
- [0f2ebdaf](https://github.com/quay/quay/commit/0f2ebdafc58867af6fac9168ed6348178ac63d45): bump moment from 2.29.2 to 2.29.4 ([#1442](https://github.com/quay/quay/issues/1442))
- [4ee715c9](https://github.com/quay/quay/commit/4ee715c9e8c27ea37a5229f9b64cf264a36817bd): bump is-my-json-valid from 2.16.0 to 2.20.6 ([#1058](https://github.com/quay/quay/issues/1058))
- [b009590c](https://github.com/quay/quay/commit/b009590c4f7f83e01adec3d26fb62d0149375710): bump ajv from 6.10.2 to 6.12.6 ([#1112](https://github.com/quay/quay/issues/1112))
- [4176c498](https://github.com/quay/quay/commit/4176c498f50b20f382953a649dfd67efd25a17ad): bump moment from 2.17.1 to 2.29.2 ([#1236](https://github.com/quay/quay/issues/1236))
- [723fd599](https://github.com/quay/quay/commit/723fd59918a30a073aadd3ea70f1a01964d7f8df): bump url-parse from 1.5.8 to 1.5.9 ([#1168](https://github.com/quay/quay/issues/1168))
- [4b4f16e1](https://github.com/quay/quay/commit/4b4f16e1b4bb24bea0a9e0d848baaab481de2e44): bump url-parse from 1.5.6 to 1.5.8 ([#1151](https://github.com/quay/quay/issues/1151))
- [49c56aa1](https://github.com/quay/quay/commit/49c56aa1c5c7e009df842d5f2825d7d9b357d58c): bump url-parse from 1.5.2 to 1.5.6 ([#1125](https://github.com/quay/quay/issues/1125))
- [c96d1fbc](https://github.com/quay/quay/commit/c96d1fbc1903aef8e28eae90afa9216e57ccebee): bump protobuf from 3.12.2 to 3.15.0 ([#1110](https://github.com/quay/quay/issues/1110))
- [102705c9](https://github.com/quay/quay/commit/102705c9469a6c5624308a31b78d10cb17a00ddd): bump pillow from 8.3.2 to 9.0.0 ([#1059](https://github.com/quay/quay/issues/1059))
- [e7e093b0](https://github.com/quay/quay/commit/e7e093b0a6c863930594eb4aad1db48289860bc9): bump qs from 6.3.1 to 6.3.3 ([#1086](https://github.com/quay/quay/issues/1086))
- [88956630](https://github.com/quay/quay/commit/889566305bc613d521c0e1d773f9773db32a5d30): bump y18n from 3.2.1 to 3.2.2 ([#1080](https://github.com/quay/quay/issues/1080))
- [21f3538f](https://github.com/quay/quay/commit/21f3538f4eb939c39c217726670288b6b745669e): bump python-ldap from 3.2.0 to 3.4.0 ([#1002](https://github.com/quay/quay/issues/1002))
- [ae516d84](https://github.com/quay/quay/commit/ae516d8481a601a58cc86bf323a607991b7b36c2): bump reportlab from 3.5.34 to 3.5.55 ([#978](https://github.com/quay/quay/issues/978))
- [288f31bb](https://github.com/quay/quay/commit/288f31bbfbced3850836ba155b602ab54d872c7d): bump pip from 20.2.3 to 21.1 ([#977](https://github.com/quay/quay/issues/977))
- [8eab6366](https://github.com/quay/quay/commit/8eab6366cdcfa273da88ab6fcd0c94681b24fb74): bump babel from 2.8.0 to 2.9.1 ([#944](https://github.com/quay/quay/issues/944))
- [66373020](https://github.com/quay/quay/commit/663730203b6f7d00076051d6e83e99b9b71f04a8): bump url-parse from 1.4.0 to 1.5.2 ([#873](https://github.com/quay/quay/issues/873))
- [299fa6d9](https://github.com/quay/quay/commit/299fa6d958ef79f33d590268368425339467905a): bump pillow from 8.3.1 to 8.3.2 ([#882](https://github.com/quay/quay/issues/882))
- [b6495343](https://github.com/quay/quay/commit/b6495343942ccd32a3227a2dd0d6646d80772d8b): bump path-parse from 1.0.5 to 1.0.7 ([#870](https://github.com/quay/quay/issues/870))
- [c5488aa3](https://github.com/quay/quay/commit/c5488aa3b52cab1c9e1391e50e0e9732f464d780): bump ssri from 6.0.1 to 6.0.2 ([#818](https://github.com/quay/quay/issues/818))
- [3c355223](https://github.com/quay/quay/commit/3c355223f17833dc5c0a8d95c1db6556b3ef9b44): bump flask-cors from 3.0.8 to 3.0.9 ([#783](https://github.com/quay/quay/issues/783))
### Builders
- [7c72e313](https://github.com/quay/quay/commit/7c72e3132e49b82279fdc3dff47db9a1c5391acc): Update scope for gitlab to include write access (PROJQUAY-5181) ([#1785](https://github.com/quay/quay/issues/1785))
- [890e2ce9](https://github.com/quay/quay/commit/890e2ce9412af7f74616a29d0fd5b023ffd8f0c9): Add scopes to the oauth call to gitlab for build trigger (PROJQUAY-5181) ([#1784](https://github.com/quay/quay/issues/1784))
- [b8d3e174](https://github.com/quay/quay/commit/b8d3e17406c546ca60789ce41c11f12e49dea9cb): Add cacert's to build agent (PROJQUAY-3819) ([#1398](https://github.com/quay/quay/issues/1398))
- [d11d45f2](https://github.com/quay/quay/commit/d11d45f208bc3c78f852bab0cb7686aa6f125c62): Send notifications on build completion (PROJQUAY-3614) ([#1346](https://github.com/quay/quay/issues/1346))
- [1d2e55b6](https://github.com/quay/quay/commit/1d2e55b63d906d949de792fd5b9481a6dd42568b): Set imagePullPolicy to always (PROJQUAY-3507) ([#1330](https://github.com/quay/quay/issues/1330))
- [3a63fd71](https://github.com/quay/quay/commit/3a63fd718788b4a0f733c1a29b8e0992083d0884): Add dnsPolicy option (PROJQUAY-3755) ([#1305](https://github.com/quay/quay/issues/1305))
- [9557cb9a](https://github.com/quay/quay/commit/9557cb9abbabc3f16b2d39484bd65267a0119473): Set default kubernetesPodman image (PROJQUAY-3586) ([#1245](https://github.com/quay/quay/issues/1245))
- [d8ae686f](https://github.com/quay/quay/commit/d8ae686f9b0992ffe73cccf945bd7a359a8a5acc): Persist build pod when DEBUG is true (PROJQUAY-3710) ([#1297](https://github.com/quay/quay/issues/1297))
- [88e86eb1](https://github.com/quay/quay/commit/88e86eb11e5095c83ce7b50716c357034dbc0273): Set backoffLimit to 1 (PROJQUAY-3587) ([#1246](https://github.com/quay/quay/issues/1246))
- [2d053e37](https://github.com/quay/quay/commit/2d053e37fbddac020e19f4c79d4ce2fc11cc5fec): add a check for expired key (PROJQUAY-3489) ([#1214](https://github.com/quay/quay/issues/1214))
- [4ecbcded](https://github.com/quay/quay/commit/4ecbcded060699388ffd008f6687c40bad4abc9f): Add DEBUG and JOB_REGISTRATION_TIMEOUT options (PROJQUAY-3395) ([#1177](https://github.com/quay/quay/issues/1177))
- [5d55ad55](https://github.com/quay/quay/commit/5d55ad55f90db0ef38ceeb999b66a15535f07bd4): Update py-bitbucket to fix bitbucket triggers (PROJQUAY-3362) ([#1170](https://github.com/quay/quay/issues/1170))
- [30ab139e](https://github.com/quay/quay/commit/30ab139ea9957655a6b9e24a1a26f41b19d09748): Remove ServerSideEncryption param from presigned URL (PROJQUAY-3180) ([#1105](https://github.com/quay/quay/issues/1105))
- [7082f867](https://github.com/quay/quay/commit/7082f867a652c8d43a9be64283d71866b160ef6c): Update boto to fix signature error (PROJQUAY-2542) ([#1087](https://github.com/quay/quay/issues/1087))
- [dce0b934](https://github.com/quay/quay/commit/dce0b934337b5f401f0107492e99e72fcb465c99): Remove socket_timeout from the redis client (PROJQUAY-2542) ([#1084](https://github.com/quay/quay/issues/1084))
- [72307569](https://github.com/quay/quay/commit/72307569e76cf89bcef4d5d3b154e1311981754d): Log errors for Github and Bitbucket trigger validation (PROJQUAY-3125) ([#144](https://github.com/quay/quay/issues/144))
- [b7d325ed](https://github.com/quay/quay/commit/b7d325ed42827db9eda2d9f341cb5a6cdfd155a6): Make single_connection_client conifgurable (PROJQUAY-3025) ([#1055](https://github.com/quay/quay/issues/1055))
### Buildman
- [1a60cbe7](https://github.com/quay/quay/commit/1a60cbe7fbdd391f073035d94596bbad8f8c0842): add SLO metric that calculates build success (PROJQUAY-4486) ([#1609](https://github.com/quay/quay/issues/1609))
- [ea67af5a](https://github.com/quay/quay/commit/ea67af5a04753df2e06007394d58bbc0667acba4): add SLO metric for time spent in queue for build jobs (PROJQUAY-4487) ([#1575](https://github.com/quay/quay/issues/1575))
- [9a11e476](https://github.com/quay/quay/commit/9a11e4760e809a4cc4ac893382ec7d2654e26a87): allow fallback on non-exception build failures (PROJQUAY-4609) ([#1605](https://github.com/quay/quay/issues/1605))
- [e3b170ea](https://github.com/quay/quay/commit/e3b170ea3f35920afee9c2c2d32c8dbf40c9bd9d): fix type when getting ec2 ami ([#1328](https://github.com/quay/quay/issues/1328))
- [a79f7b6f](https://github.com/quay/quay/commit/a79f7b6f4063b38a8caeceb38975ac0f37ea1c57): increase allowed grpc body size for log streams ([#1234](https://github.com/quay/quay/issues/1234))
- [ceb9262b](https://github.com/quay/quay/commit/ceb9262b7e5484fe7cd0e050e24c014c7e78c68c): Add EXECUTOR parameter (PROJQUAY-3278) ([#1134](https://github.com/quay/quay/issues/1134))
- [3ca44073](https://github.com/quay/quay/commit/3ca44073b17a0c42f98d44811224652a05e306cd): prevent systemd oneshot service from timing (PROJQUAY-3304) ([#1149](https://github.com/quay/quay/issues/1149))
- [32691dd8](https://github.com/quay/quay/commit/32691dd8127fc23910a80edfc84cf70ba25fb806): Set build token expiration to builder's lifetime (PROJQUAY-3281) ([#1142](https://github.com/quay/quay/issues/1142))
- [a0443340](https://github.com/quay/quay/commit/a0443340cb57d9dba4a3dea9d335cf0e3ad29679): fix multiple build retries phase (PROJQUAY-3281) ([#1139](https://github.com/quay/quay/issues/1139))
- [9b892626](https://github.com/quay/quay/commit/9b89262640022250d9c3be7b4611bc2bf1758419): configurable build job registration timeout (PROJQUAY-3280) ([#1135](https://github.com/quay/quay/issues/1135))
- [a29e64be](https://github.com/quay/quay/commit/a29e64be187a057850fea8f34b809e6699809b43): Add kubernetesPodman build option (PROJQUAY-3052) ([#1066](https://github.com/quay/quay/issues/1066))
- [eaaa3adb](https://github.com/quay/quay/commit/eaaa3adbf05422a2625946e7cc5d7999d4325430): allow use of public builder image (PROJQUAY-3179) ([#1103](https://github.com/quay/quay/issues/1103))
- [b07b44a7](https://github.com/quay/quay/commit/b07b44a7eb2b70282e0cfb07362d33fc3666c358): fix kubernetes not returning correct running count (PROJQUAY-3169) ([#1099](https://github.com/quay/quay/issues/1099))
- [f5b9492a](https://github.com/quay/quay/commit/f5b9492ac62df7a9b3ee741fc7ef8aba36028b72): Add proxy variables to builds if they exist (PROJQUAY-2120) ([#834](https://github.com/quay/quay/issues/834))
- [bfb8602d](https://github.com/quay/quay/commit/bfb8602d5ae1b3eb56fe57a381a6939fb60f98be): fix vm image name in startup script (PROJQUAY-2120) ([#811](https://github.com/quay/quay/issues/811))
- [945e038f](https://github.com/quay/quay/commit/945e038f1476de857b1b7992e1ce60dc5ff76458): cast job_status to string for metric
### Bump
- [b21400b9](https://github.com/quay/quay/commit/b21400b90d46ff1d6a989c2b3008769420bbd608): Bump to redeploy Quay pods to reflect new endpoint (PROJQUAY-2056) ([#1327](https://github.com/quay/quay/issues/1327))
### CI
- [e566560f](https://github.com/quay/quay/commit/e566560fee3ab584e9eccb612925d830facbb142): Commenting arm docker build (PROJQUAY-0000) ([#1522](https://github.com/quay/quay/issues/1522))
### CONTRIBUTING
- [f0edbceb](https://github.com/quay/quay/commit/f0edbceb5b24c1a5298eeece77e53de9ef643372): document backporting process ([#1043](https://github.com/quay/quay/issues/1043))
### Cache
- [ccf6ada1](https://github.com/quay/quay/commit/ccf6ada16a1feac137a8aa7ea828a99df66586ac): handle uncaught redis exception (PROJQUAY-2614) ([#907](https://github.com/quay/quay/issues/907))
- [3dde3646](https://github.com/quay/quay/commit/3dde364615ae3f2b839fb38b7e791805e4243c3c): py2 compatibility, kwargs after named args (PROJQUAY-2101) ([#859](https://github.com/quay/quay/issues/859))
- [cd6871c1](https://github.com/quay/quay/commit/cd6871c14f5e017d70d99664ccde89ccac9e4366): add support for redis cluster mode (PROJQUAY-2101) ([#810](https://github.com/quay/quay/issues/810))
- [1180ea99](https://github.com/quay/quay/commit/1180ea99fae3787eccfa53801af6199d3af3bcac): remove GlobalLock from redis model cache (PROJQUAY-1902) ([#755](https://github.com/quay/quay/issues/755))
- [780685c4](https://github.com/quay/quay/commit/780685c490097ce7cf9515e0642505a45817df6a): add Redis model cache implementation (PROJQUAY-788) ([#444](https://github.com/quay/quay/issues/444))
### Certs
- [0cb8bde0](https://github.com/quay/quay/commit/0cb8bde0f8b63f807d18f0a9f584d476cac73f12): Load certs with both extra_ca_cert_ and extra_ca_certs/ prefix (PROJQUAY-3593)
### Cherrypick
- [e9743d3d](https://github.com/quay/quay/commit/e9743d3d9588cb73e1aa260529ddac5553c21bfb): commit f2417670 from master (PROJQUAY-6895) ([#2796](https://github.com/quay/quay/issues/2796))
### Chore
- [2f43058d](https://github.com/quay/quay/commit/2f43058d817c5de952751bc31132a5d9aea7bc39): revert [#3714](https://github.com/quay/quay/issues/3714) and remove pip from requirements.txt in workflow ([#3729](https://github.com/quay/quay/issues/3729))
- [f62ee576](https://github.com/quay/quay/commit/f62ee57673b02fbac264b8ca204bd13085428221): upgrade jinja to 3.1.6 (PROJQUAY-8657) ([#3718](https://github.com/quay/quay/issues/3718))
- [80d8af47](https://github.com/quay/quay/commit/80d8af47d2c2fc190592dcbe1a2896df5f8dbaee): removing pip from requirements.txt file ([#3714](https://github.com/quay/quay/issues/3714))
- [dc67d473](https://github.com/quay/quay/commit/dc67d473e7a3820e90d71708793721e62f416667): v3.9.1 changelog bump (PROJQUAY-5937) ([#2154](https://github.com/quay/quay/issues/2154))
- [ea71ac15](https://github.com/quay/quay/commit/ea71ac151b10bc2f64f94d5a579e6c4fe3134b76): Bump pushgateway to 1.6.0 (PROJQUAY-5874) ([#2058](https://github.com/quay/quay/issues/2058))
- [0b3c93f0](https://github.com/quay/quay/commit/0b3c93f0e5a2f08f5e2d05266cb927a71076e248): Add build dependency for reportlab ([#2137](https://github.com/quay/quay/issues/2137))
- [a2e23e68](https://github.com/quay/quay/commit/a2e23e68d1058c88924ddba34c74144532845afb): Add build dependencies for lxml 4.9.2 ([#2136](https://github.com/quay/quay/issues/2136))
- [e8acc54f](https://github.com/quay/quay/commit/e8acc54fb01b1745a25e74c20ba4dec2254c3441): fix build of PyYAML on linux/ppc64le ([#2114](https://github.com/quay/quay/issues/2114))
- [44db77ba](https://github.com/quay/quay/commit/44db77ba6c3acd1f3b1a946c01c73749c3f15914): Reformat python scripts in config-tool
- [9351d03a](https://github.com/quay/quay/commit/9351d03a63f6f3eb6e16e7324cb9420b69794fc6): Merge config-tool/.github into .github
- [bb4a9c9d](https://github.com/quay/quay/commit/bb4a9c9d184ff3563aeed6e390f7b949e6a7f4b2): Rename github.com/quay/config-tool to github.com/quay/quay/config-tool
- [09d5ab46](https://github.com/quay/quay/commit/09d5ab4664f0d74fcd9ebc11f745ea134fdd3ede): Use config-tool from this repo
- [3298995a](https://github.com/quay/quay/commit/3298995a79cde7dba03645c4593bd11699d6c0c7): Do not require ticket for build(deps-dev) ([#2081](https://github.com/quay/quay/issues/2081))
- [1c85c563](https://github.com/quay/quay/commit/1c85c563b9db80e2d2b1aee583492e7afe9ba590): use isinstance to check instance type ([#2070](https://github.com/quay/quay/issues/2070))
- [0429d796](https://github.com/quay/quay/commit/0429d79696c5a716cb05d5bbe82d68c9435445be): Move config-tool into its own directory
- [95a51576](https://github.com/quay/quay/commit/95a51576d52e4762de76eeb4db483c44ab6e13f0): Fix regexp in pull_request_linting.yaml ([#2054](https://github.com/quay/quay/issues/2054))
- [cb82a468](https://github.com/quay/quay/commit/cb82a4681b62e706596ab8a3c01b7c08207dce7a): Bump dependencies (PROJQUAY-5630) ([#211](https://github.com/quay/quay/issues/211))
- [49efb78c](https://github.com/quay/quay/commit/49efb78ce39e5980fcbf106e6a2c81f7e89e0a4a): Use stable Cython ([#2025](https://github.com/quay/quay/issues/2025))
- [24b5fed0](https://github.com/quay/quay/commit/24b5fed01cddcf6fa5e00956e27653bcd8198ada): Use conventional-commit-checker-action for Jira check (PROJQUAY-5672) ([#2023](https://github.com/quay/quay/issues/2023))
- [97c5a722](https://github.com/quay/quay/commit/97c5a7226043ce3c4283f02580ea97bf8420651d): Bump PyYAML ([#2022](https://github.com/quay/quay/issues/2022))
- [e3c6e257](https://github.com/quay/quay/commit/e3c6e2573cfa8136039af531c79bcf5ae4524c86): Use latest go-toolset for config-tool ([#2020](https://github.com/quay/quay/issues/2020))
- [290ebbe2](https://github.com/quay/quay/commit/290ebbe2c04f338dca04b29b533d17e50449624e): Create Quay PR from the same push event
- [11cc5961](https://github.com/quay/quay/commit/11cc596145b5732c7704bda2bb88bca3c98f0233): Use DEPLOY_PAT so that GitHub reacts on new tags
- [4b95f4dd](https://github.com/quay/quay/commit/4b95f4dddee665d870fe1b5fdf25221725d28cbd): Create PR against Quay for new tags ([#212](https://github.com/quay/quay/issues/212))
- [cc4bb0cc](https://github.com/quay/quay/commit/cc4bb0cc8eb59a19e4b326f3adcd8ea91c153d73): Use buildx v0.11.0-rc2 ([#1960](https://github.com/quay/quay/issues/1960)) ([#1971](https://github.com/quay/quay/issues/1971))
- [ef31a820](https://github.com/quay/quay/commit/ef31a82021e5a2d3ee64e1aa203636145d93c02e): v3.9.0 changelog bump (PROJQUAY-5065) ([#1944](https://github.com/quay/quay/issues/1944))
- [6a664d8c](https://github.com/quay/quay/commit/6a664d8cb0a569c78d922eef24e5e02ba6df38a3): update ppc64le builder ([#1904](https://github.com/quay/quay/issues/1904))
- [8e326f27](https://github.com/quay/quay/commit/8e326f278c02546ee17bfc9b677b232566d86087): Use external builders ([#1898](https://github.com/quay/quay/issues/1898))
- [42c9ebc4](https://github.com/quay/quay/commit/42c9ebc45cfe5b402c5c5ed831c399d570342fe6): Delete outdated k8 manifests (PROJQUAY-5490) ([#1880](https://github.com/quay/quay/issues/1880))
- [53e43942](https://github.com/quay/quay/commit/53e439427287029e221c625691346b1c0b12aaa0): Remove Docker Build jobs (PROJQUAY-5519) ([#1888](https://github.com/quay/quay/issues/1888))
- [d49dbd15](https://github.com/quay/quay/commit/d49dbd1515b3a17d21127b881461d333045552a5): Update db data for UI tests ([#1874](https://github.com/quay/quay/issues/1874))
- [80602e04](https://github.com/quay/quay/commit/80602e0421fc164ae358006a82ef5c6469479f04): Fix UI tests (PROJQUAY-5424) ([#1858](https://github.com/quay/quay/issues/1858))
- [8a235155](https://github.com/quay/quay/commit/8a235155ca9e111c3d811f2f808230a50720473d): Remove cachito magic for PyPDF2 ([#1838](https://github.com/quay/quay/issues/1838))
- [b4418062](https://github.com/quay/quay/commit/b4418062f93ddf45e1c1aad0a77b0b2193f1d2ef): Ensure use of HTTP 1.1 when proxying storage (PROJQUAY-5140) ([#1825](https://github.com/quay/quay/issues/1825))
- [fa50c70e](https://github.com/quay/quay/commit/fa50c70ed0cb86fa67141f6a34c772aa8bd154c0): Simplify base image (PROJQUAY-4837) ([#1709](https://github.com/quay/quay/issues/1709))
- [0ef6c67a](https://github.com/quay/quay/commit/0ef6c67a9e5d4f2cf69702eea09e4c5880811d8c): Fixes for local-dev-up-with-clair ([#1819](https://github.com/quay/quay/issues/1819))
- [58e0958c](https://github.com/quay/quay/commit/58e0958c67b7872c2fef676b5fc8eabc61a31fa1): Pin distribution-spec conformance tests ([#1809](https://github.com/quay/quay/issues/1809))
- [a8bf1c98](https://github.com/quay/quay/commit/a8bf1c98cfa5525e3e89aa1542240f24cfe756b0): Downgrade cryptography to 3.3.2 (PROJQUAY-5120) ([#1803](https://github.com/quay/quay/issues/1803))
- [e4df7102](https://github.com/quay/quay/commit/e4df710253889eacef0e2e985331c2c425e75d28): Add setuptools-rust as a build dependency ([#1788](https://github.com/quay/quay/issues/1788))
- [4d1989cc](https://github.com/quay/quay/commit/4d1989cc8d0d2fa6e7aeaed92b0cf8a868e48abe): Bump pyOpenSSL and cryptography (PROJQUAY-5120) ([#1777](https://github.com/quay/quay/issues/1777))
- [b7340739](https://github.com/quay/quay/commit/b7340739594da8ca7d2c522837ed2bf293bbecc3): Bump Authlib (PROJQUAY-5120) ([#1773](https://github.com/quay/quay/issues/1773))
- [8b14160c](https://github.com/quay/quay/commit/8b14160cea357018abb711c25b7c169bb9f8eabf): Bump config-tool to 1.15 (PROJQUAY-3643) ([#1763](https://github.com/quay/quay/issues/1763))
- [77b91045](https://github.com/quay/quay/commit/77b91045cc58716cdb47cd8f17c67110a4b6be9f): Bump http-swagger (PROJQUAY-3643) ([#198](https://github.com/quay/quay/issues/198))
- [61913f86](https://github.com/quay/quay/commit/61913f86f83d54c1c7303c973db761f1c4a23791): bump config-tool version to latest (PROJQUAY-5048) ([#1754](https://github.com/quay/quay/issues/1754))
- [ab78f63d](https://github.com/quay/quay/commit/ab78f63d08594348427742a405be3b322ca714a9): Remove appr dependencies (PROJQUAY-4992) ([#1728](https://github.com/quay/quay/issues/1728))
- [9cc94feb](https://github.com/quay/quay/commit/9cc94feb5b37d634ea81e71dc8c60308982a7044): remove yapf (PROJQUAY-4865) ([#1693](https://github.com/quay/quay/issues/1693))
- [4efa48e3](https://github.com/quay/quay/commit/4efa48e3e074512b5938f38281b122b2e8c76a37): Use GitHub Actions cache for Docker Build jobs (PROJQUAY-4970) ([#1710](https://github.com/quay/quay/issues/1710))
- [ff498b39](https://github.com/quay/quay/commit/ff498b39812379c611f49621feae492dbb2f5297): v3.8.1 changelog bump (PROJQUAY-4716) ([#1721](https://github.com/quay/quay/issues/1721))
- [6e8e2d2f](https://github.com/quay/quay/commit/6e8e2d2fe71bb243f448f4b07e7e99d5865d0e15): remove deprecated appr code (PROJQUAY-4992) ([#1718](https://github.com/quay/quay/issues/1718))
- [6c454444](https://github.com/quay/quay/commit/6c45444496c104fa29165934ce8aac43840acfb3): Update Dockerfile to reduce size of image (PROJQUAY-4837) ([#1675](https://github.com/quay/quay/issues/1675)) ([#1681](https://github.com/quay/quay/issues/1681))
- [589fbb49](https://github.com/quay/quay/commit/589fbb49892c674637bf78f8004e1f4805de1822): Update Dockerfile to reduce size of image (PROJQUAY-4837) ([#1675](https://github.com/quay/quay/issues/1675))
- [cdb52ed0](https://github.com/quay/quay/commit/cdb52ed023c8222f2eeb95a1c71c403a06655ed8): Add server side assembly of chunked metadata for RADOSGW driver (PROJQUAY-4592) ([#1557](https://github.com/quay/quay/issues/1557))
- [f4828fde](https://github.com/quay/quay/commit/f4828fde5cecac46f898d88037b41a1e6e2bee6b): Add georeplication variable check (PROJQUAY-4363) ([#1499](https://github.com/quay/quay/issues/1499))
- [8e1fba48](https://github.com/quay/quay/commit/8e1fba48420087eadaf57ed6892780e44a767cdf): Fix startup script ([#1402](https://github.com/quay/quay/issues/1402))
- [cf52f5e3](https://github.com/quay/quay/commit/cf52f5e3716009e87d251d71a7057343b81d33e6): Use Python 3.9 ([#1382](https://github.com/quay/quay/issues/1382))
- [5eaf0584](https://github.com/quay/quay/commit/5eaf0584dbc87d7eeb135de63bbea4c7d40a1fa0): Run mypy as CI job ([#1363](https://github.com/quay/quay/issues/1363))
- [13f8e0c4](https://github.com/quay/quay/commit/13f8e0c4b3ac6b48503cadb8c191832f499e61c0): Rebuild quay image if requirements.txt is changed ([#1342](https://github.com/quay/quay/issues/1342))
- [c2ceda5a](https://github.com/quay/quay/commit/c2ceda5a26d3106ef6672fa31e8212ba4cb902ab): various small changes to fix exceptions, remove unused code ([#1295](https://github.com/quay/quay/issues/1295))
- [2d56a8df](https://github.com/quay/quay/commit/2d56a8dfba0cf305a43aad82af382bc48b06911a): add logging during instance service key generation ([#1276](https://github.com/quay/quay/issues/1276))
- [5c226105](https://github.com/quay/quay/commit/5c226105e83b5884d4832ae4bcd47771e362859c): Fix cachito issue with pypdf (PROJQUAY-3184) ([#1223](https://github.com/quay/quay/issues/1223))
- [a3ad25c4](https://github.com/quay/quay/commit/a3ad25c48a04bd3319f1b393e0b1f2886a6269b9): Remove unneeded flags fromt he config schema ([#1152](https://github.com/quay/quay/issues/1152))
- [2344adb8](https://github.com/quay/quay/commit/2344adb8194bd026572903f8784003ebd8e81b7c): remove unused tools (PROJQUAY-0) ([#1113](https://github.com/quay/quay/issues/1113))
- [9bdbba6f](https://github.com/quay/quay/commit/9bdbba6ff946042709aa91bb9d80193120aba785): Remove unused files ([#1067](https://github.com/quay/quay/issues/1067))
- [65100439](https://github.com/quay/quay/commit/65100439f6dd70b12db2276ec61cff99704bfa4e): download aws ip ranges via github workflow ([#1041](https://github.com/quay/quay/issues/1041))
- [b7037d9c](https://github.com/quay/quay/commit/b7037d9c50bf7a282c7983577b380cfc401b7825): Bump up config-tool version v0.1.9 ([#992](https://github.com/quay/quay/issues/992))
- [2ffc12b3](https://github.com/quay/quay/commit/2ffc12b3eb5e36c070df80fcd5ffffa9593fd22a): cleanup remaining artifacts remaining related to aci signing (PROJQUAY-2792) ([#968](https://github.com/quay/quay/issues/968))
- [ae129b45](https://github.com/quay/quay/commit/ae129b45e9db29f4e787e0190afc6af4c29ec277): Bump up config-tool version v0.1.8 ([#984](https://github.com/quay/quay/issues/984))
- [c8092069](https://github.com/quay/quay/commit/c8092069a296726fe888f6c3b8f4e15d8f7958e8): Bump up config-tool version ([#983](https://github.com/quay/quay/issues/983))
- [ba08ddd7](https://github.com/quay/quay/commit/ba08ddd707e7ac4b6e29460deef533eb23c6036f): Bump up config-tool version ([#982](https://github.com/quay/quay/issues/982))
- [bbacf232](https://github.com/quay/quay/commit/bbacf2321facf0fbb7fdc407799623943fa14fea): bump gevent related packages' version (PROJQUAY-2821) ([#979](https://github.com/quay/quay/issues/979))
- [8ef0aff8](https://github.com/quay/quay/commit/8ef0aff83dffac3ae32938dc9105a5926a94c10d): improve check for JIRA ticket (PROJQUAY-2623) ([#919](https://github.com/quay/quay/issues/919))
- [c90b444f](https://github.com/quay/quay/commit/c90b444f8322a425ebd718809eac25c3c7cae265): Provide timestamps on container startup including registry, mirror and config container ([#921](https://github.com/quay/quay/issues/921))
- [16dcebf1](https://github.com/quay/quay/commit/16dcebf101f807738868711246614a9dd10f5566): build and publish workflow (PROJQUAY-2556)
- [79703a91](https://github.com/quay/quay/commit/79703a91760a7e7fbbadf9ebec6a85fe72a35b78): Move qemu outside of quay repo to its github repo (PROJQUAY-2342) ([#866](https://github.com/quay/quay/issues/866))
- [47a1fdd3](https://github.com/quay/quay/commit/47a1fdd38ecbaffb460ebb4c6d43da4c14986221): remove ui elements for account recovery mode (PROJQUAY-970) ([#853](https://github.com/quay/quay/issues/853))
- [7d7eb755](https://github.com/quay/quay/commit/7d7eb75557fdc58a6c40536ccc807522659bd0d9): return zope.interface to requirements-osbs.txt (PROJQUAY-1535) ([#854](https://github.com/quay/quay/issues/854))
- [0999baa2](https://github.com/quay/quay/commit/0999baa29e76ee7c3118af75bb06b7bd681b66de): fix rediscluster cache config key name (PROJQUAY-2101) ([#849](https://github.com/quay/quay/issues/849))
- [a839a78e](https://github.com/quay/quay/commit/a839a78eb52e612a3f99c573ce1a552c5bb5e7a0): allows Quay to run for account recoveries (PROJQUAY-970) ([#793](https://github.com/quay/quay/issues/793))
- [4880c776](https://github.com/quay/quay/commit/4880c776e264e3fbf553418eff6656c68e5f60f2): remove node modules from final container (PROJQUAY-1822) ([#788](https://github.com/quay/quay/issues/788))
- [4ad5a458](https://github.com/quay/quay/commit/4ad5a458c2927be557f876a5e66928a02c67f87d): remove uploading filtering from imagestorage queries (PROJQUAY-1914) ([#764](https://github.com/quay/quay/issues/764))
- [8921114d](https://github.com/quay/quay/commit/8921114d41faa184a787a93802394f5ab783d488): v3.6.0-alpha.9 changelog bump (PROJQUAY-1486) ([#763](https://github.com/quay/quay/issues/763))
- [0ffe9cee](https://github.com/quay/quay/commit/0ffe9ceecac456ab2b722459aa5aebe70c902fe9): correct chnglog params (PROJQUAY-1486) ([#762](https://github.com/quay/quay/issues/762))
- [addaeac0](https://github.com/quay/quay/commit/addaeac04aaab3d887258f53fdbb2fc85240bd62): fix release image tag to retain leading 'v' (PROJQUAY-1486) ([#739](https://github.com/quay/quay/issues/739))
- [ce7aa978](https://github.com/quay/quay/commit/ce7aa97802aac4118894cc5e97a81e431fe79f35): bump version to 3.6.0 (PROJQUAY-1861) ([#738](https://github.com/quay/quay/issues/738))
- [ecc125ff](https://github.com/quay/quay/commit/ecc125ff93c5a8328290195ab7dc2156a8ce32df): v3.6.0-alpha.8 changelog bump (PROJQUAY-1486) ([#732](https://github.com/quay/quay/issues/732))
- [166d17ab](https://github.com/quay/quay/commit/166d17ab4fb9ab65ffb0f59c35246e406ffbdf52): correct cut-release.yml (PROJQUAY-1486) ([#731](https://github.com/quay/quay/issues/731))
- [b54c8999](https://github.com/quay/quay/commit/b54c89997f64b66431accacc348e8fcefb02a42c): v3.6.0-alpha.7 changelog bump (PROJQUAY-1486) ([#730](https://github.com/quay/quay/issues/730))
- [bfc9d75c](https://github.com/quay/quay/commit/bfc9d75cab49df0bfd901a355a9bcb53bfeb5407): fix cut-release.yml (PROJQUAY-1468) ([#729](https://github.com/quay/quay/issues/729))
- [6c7dcb84](https://github.com/quay/quay/commit/6c7dcb8425debd7f9fcfed466a93ec40ad62fb1d): correct git-chglog config (PROJQUAY-1468) ([#728](https://github.com/quay/quay/issues/728))
- [43891120](https://github.com/quay/quay/commit/438911205aed1f543a97f0226319449eac3b927c): v3.6.0-alpha.6 changelog bump (PROJQUAY-1486) ([#727](https://github.com/quay/quay/issues/727))
- [043dbffc](https://github.com/quay/quay/commit/043dbffc59ce92fb125e678db579e7db45590efd): fix changelog template (PROJQUAY-1486) ([#726](https://github.com/quay/quay/issues/726))
- [03347285](https://github.com/quay/quay/commit/033472855fea2226925932486f4a98d8b960a7f7): parse new CHANGELOG.md format (PROJQUAY-1486) ([#725](https://github.com/quay/quay/issues/725))
- [bc476ab2](https://github.com/quay/quay/commit/bc476ab2486b898a28129b1642f32d5ee4e85615): v3.6.0-alpha.2 changelog bump (PROJQUAY-1486) ([#721](https://github.com/quay/quay/issues/721))
- [635dd6a7](https://github.com/quay/quay/commit/635dd6a73a1d52e9de8690bc1e59277167f7da25): import missing logging.config module ([#706](https://github.com/quay/quay/issues/706))
- [5845afd4](https://github.com/quay/quay/commit/5845afd4e032304319b1764e0589e93ae34e9364): use `--no-cache-dir` flag to `pip` in dockerfiles, to save space ([#529](https://github.com/quay/quay/issues/529))
### Chore(Dockerfile)
- [0f7fdb7e](https://github.com/quay/quay/commit/0f7fdb7e847df7ac68154c7627486c5ca048736c): add local-dev-env build stage (PROJQUAY-2501) ([#883](https://github.com/quay/quay/issues/883))
### Chore: V3.6.3 Changelog Bump (Https
- [62e2eac1](https://github.com/quay/quay/commit/62e2eac1b083dc6a6c0cdc882f8494ef9dfcf999): //issues.redhat.com/browse/PROJQUAY-3028) ([#1118](https://github.com/quay/quay/issues/1118))
### Chore: V3.6.4 Changelog Bump (Https
- [992bc5c3](https://github.com/quay/quay/commit/992bc5c3ccb1474c0dc1d5a576363dc9d01ff2d7): //issues.redhat.com/browse/PROJQUAY-3335) ([#1162](https://github.com/quay/quay/issues/1162))
### Chore: V3.6.5 Changelog Bump (Https
- [81db4e84](https://github.com/quay/quay/commit/81db4e84bb415a475956dbb6c76bbd11080b09b7): //issues.redhat.com/browse/PROJQUAY-3354) ([#1211](https://github.com/quay/quay/issues/1211))
### Chore: V3.6.6 Changelog Bump (Https
- [d8a76c0d](https://github.com/quay/quay/commit/d8a76c0d3c10d4ff08f55bfddde181b9611007b5): //issues.redhat.com/browse/PROJQUAY-3635) ([#1278](https://github.com/quay/quay/issues/1278))
### Chore: V3.6.8 Changelog Bump (Https
- [f69b1309](https://github.com/quay/quay/commit/f69b1309a01d3e4d73dddc2d829e7e188b6bb04e): //issues.redhat.com/browse/PROJQUAY-3990) ([#1419](https://github.com/quay/quay/issues/1419))
### Chore: V3.6.9 Changelog Bump (Https
- [b44df459](https://github.com/quay/quay/commit/b44df459aaa511a5e44f8b427e9b6a8feda501ee): //issues.redhat.com/browse/PROJQUAY-4192) ([#1466](https://github.com/quay/quay/issues/1466))
### Chore: V3.7.0 Changelog Bump (Https
- [e85372d0](https://github.com/quay/quay/commit/e85372d00586217dd8ec1f4b808c6d2534dea28e): //issues.redhat.com/browse/PROJQUAY-2411) ([#1337](https://github.com/quay/quay/issues/1337))
### Chore: V3.7.1 Changelog Bump (Https
- [e76db133](https://github.com/quay/quay/commit/e76db133fcd62b07f6c99c420410ef9eca12dd73): //issues.redhat.com/browse/PROJQUAY-3836) ([#1372](https://github.com/quay/quay/issues/1372))
### Chore: V3.7.10 Changelog Bump (Https
- [612a6537](https://github.com/quay/quay/commit/612a65379d261931786a5a8540b2373afcbb9561): //issues.redhat.com/browse/PROJQUAY-4627) ([#1591](https://github.com/quay/quay/issues/1591))
### Chore: V3.7.11 Changelog Bump (Https
- [a2aa6397](https://github.com/quay/quay/commit/a2aa6397af6a12ab10b8a985e75ab7c67d9f19fb): //issues.redhat.com/browse/PROJQUAY-4790) ([#1650](https://github.com/quay/quay/issues/1650))
### Chore: V3.7.3 Changelog Bump (Https
- [a55c63e7](https://github.com/quay/quay/commit/a55c63e7117438c483c78cd17c60e0491ab498cd): //issues.redhat.com/browse/PROJQUAY-3989) ([#1420](https://github.com/quay/quay/issues/1420))
### Chore: V3.7.4 Changelog Bump (Https
- [a5279983](https://github.com/quay/quay/commit/a52799830235ae67162e35e8cc6ddcca999343a2): //issues.redhat.com/browse/PROJQUAY-4050) ([#1446](https://github.com/quay/quay/issues/1446))
### Chore: V3.7.5 Changelog Bump (Https
- [cc26275d](https://github.com/quay/quay/commit/cc26275d999ebac469c1cc80211ea3f3fd3c7652): //issues.redhat.com/browse/PROJQUAY-4172) ([#1458](https://github.com/quay/quay/issues/1458))
### Chore: V3.7.6 Changelog Bump (Https
- [e1a14f5c](https://github.com/quay/quay/commit/e1a14f5c53b18f8db967131572c43b7588ad51aa): //issues.redhat.com/browse/PROJQUAY-4237) ([#1480](https://github.com/quay/quay/issues/1480))
### Chore: V3.7.7 Changelog Bump (Https
- [fcdd0e12](https://github.com/quay/quay/commit/fcdd0e12bf299bcf362799d1ffe8051ceb90ce71): //issues.redhat.com/browse/PROJQUAY-4286) ([#1508](https://github.com/quay/quay/issues/1508))
### Chore: V3.7.8 Changelog Bump (Https
- [292d33f2](https://github.com/quay/quay/commit/292d33f2922df5e3cdae72d839a537c3d7fa5df6): //issues.redhat.com/browse/PROJQUAY-4385) ([#1517](https://github.com/quay/quay/issues/1517))
### Chore: V3.7.9 Changelog Bump (Https
- [2ec6405a](https://github.com/quay/quay/commit/2ec6405a15f6d2b8f3a827ca511ae8195e38942e): //issues.redhat.com/browse/PROJQUAY-4478) ([#1568](https://github.com/quay/quay/issues/1568))
### Ci
- [b620e304](https://github.com/quay/quay/commit/b620e304c501cbd36d691bd99acd96596d15bcfd): updating user for s390x test instance to wfuser ([#3525](https://github.com/quay/quay/issues/3525))
- [07c8a75f](https://github.com/quay/quay/commit/07c8a75fa18ab4da5abad2ede24347419656c793): Check arm64 builds in CI (PROJQUAY-4038) ([#1431](https://github.com/quay/quay/issues/1431))
- [202973a1](https://github.com/quay/quay/commit/202973a1b1bf516ae46792ee50775dadf21b713c): Update golang version in CI (PROJQUAY-1605)
- [e2921d7a](https://github.com/quay/quay/commit/e2921d7af8d3d2ed3bc8f44c939bfcc6b340c52b): Enable workflow dispatch for build and publish (PROJQUAY-3310) ([#1155](https://github.com/quay/quay/issues/1155))
- [c7c4c0dc](https://github.com/quay/quay/commit/c7c4c0dc4ca9681482a100a831950355634c3b61): Update funcparserlib version (PROJQUAY-2520) ([#893](https://github.com/quay/quay/issues/893))
- [e6011cff](https://github.com/quay/quay/commit/e6011cff5ba539a51a25ec2f0298068f63819c6e): include optional merge commit number in commit check job (PROJQUAY-1486) ([#742](https://github.com/quay/quay/issues/742))
### Clean.Sh
- [6b5e7f50](https://github.com/quay/quay/commit/6b5e7f506fe6cbb124ede711d9480e5f39eb70f1): don't remove webfonts dir since its now versioned ([#1025](https://github.com/quay/quay/issues/1025))
### Cleanup
- [687abaa2](https://github.com/quay/quay/commit/687abaa2d73eaf99dea5c0ddf078ec6fc656ce30): Removing requirements-nover.txt (PROJQUAY-2985) ([#1038](https://github.com/quay/quay/issues/1038))
### Cleanup
- [304087f9](https://github.com/quay/quay/commit/304087f9c911071b083d87fce798b12d52f9ed0d): Remove old validation code (PROJQUAY-4606) ([#1562](https://github.com/quay/quay/issues/1562))
### Compliance
- [ad4bb6f1](https://github.com/quay/quay/commit/ad4bb6f185d312f582ad8a174fce498b95c2a5dd): Move export screening to RHSSO class (PROJQUAY-2056) ([#1302](https://github.com/quay/quay/issues/1302))
### Conf
- [a07ba480](https://github.com/quay/quay/commit/a07ba480559ef71981e536e2243dd190c2bd79dd): fix supervisord chunk worker template ([#1259](https://github.com/quay/quay/issues/1259))
- [7687e16f](https://github.com/quay/quay/commit/7687e16fc1d9d38192d8903ac38c136e2b12d3e2): replace prometheus aggregator w/ pushgateway
### Conf/Init
- [2b3d4f7b](https://github.com/quay/quay/commit/2b3d4f7bf9e255195cbfbab4d57232ac2477a342): add validate supervisord config test
- [51bdb627](https://github.com/quay/quay/commit/51bdb627f9656bddf80bc1b3cf968d633676ee24): remove service directory
### Conf/Nginx
- [f45c68eb](https://github.com/quay/quay/commit/f45c68ebf2635eeadbaeaf11ce5df9e215ae62d1): mark beginning of string in oauth location match ([#1550](https://github.com/quay/quay/issues/1550))
### Config
- [6eeb45b7](https://github.com/quay/quay/commit/6eeb45b7c003d582d43cba88f46ecca16d2fc1aa): Set feature flag default for new vulnerability notifications to True ([#1995](https://github.com/quay/quay/issues/1995))
- [9a7239e8](https://github.com/quay/quay/commit/9a7239e8746c2f0c7ec6af28105c777d9d6b5341): updating quota defaults (PROJQUAY-5546) ([#1901](https://github.com/quay/quay/issues/1901))
- [34a6e5fe](https://github.com/quay/quay/commit/34a6e5fea85e13bd00da5e4b8729d6adf6e59f70): clean upload folder by default (PROJQUAY-4395) ([#1731](https://github.com/quay/quay/issues/1731))
- [6bbfdf5e](https://github.com/quay/quay/commit/6bbfdf5e78e37eeafb3f422253785cf0ddc590a7): Remove whitespace from config (PROJQUAY-4666) ([#1596](https://github.com/quay/quay/issues/1596))
- [ff8043dd](https://github.com/quay/quay/commit/ff8043dd85732aa96ac7d90218a4ef416ef56cea): Add conftest mediatypes to default Quay configuration (PROJQUAY-4614) ([#1567](https://github.com/quay/quay/issues/1567))
- [e659e809](https://github.com/quay/quay/commit/e659e8092a17a1d78aa1fedbd8c8c91c2bf83d21): Update config-tool to v0.1.11 (PROJQUAY-3318) ([#1195](https://github.com/quay/quay/issues/1195))
- [c1cc7c53](https://github.com/quay/quay/commit/c1cc7c531d060723ed92ea60de1119987a202c30): Allow envelope mediatype (PROJQUAY-3386) ([#1196](https://github.com/quay/quay/issues/1196))
- [c02f912f](https://github.com/quay/quay/commit/c02f912f4364ab1a4299a9e576f99825cadaefbb): Update config-tool version to v0.1.10 (PROJQUAY-3125) ([#1078](https://github.com/quay/quay/issues/1078))
- [c507eeff](https://github.com/quay/quay/commit/c507eeff2eae61efe1a18a4b0e6addce4d37bc5a): define default oci artifact types (PROJQUAY-2334) ([#877](https://github.com/quay/quay/issues/877))
- [509884f6](https://github.com/quay/quay/commit/509884f6e01b3175b09515188dce7eb2e6ddb68e): Allow download of unvalidated config (PROJQUAY-1925)
### Config
- [4ebad4dc](https://github.com/quay/quay/commit/4ebad4dcd8b4d7562171e5c7f56ee133305cb932): Updating Cosign SBOM Media Types on Quay (PROJQUAY-4591) ([#1554](https://github.com/quay/quay/issues/1554))
### Config.Py
- [d14da17a](https://github.com/quay/quay/commit/d14da17a401caed79e87a3685b554a0007e5de51): Add support for source containers (PROJQUAY-2271) ([#954](https://github.com/quay/quay/issues/954))
### Configtool
- [a1c33a95](https://github.com/quay/quay/commit/a1c33a95b2c9f495fde520b50307b3f1efc33e25): Add option to override Azure endpoint (PROJQUAY-891) ([#164](https://github.com/quay/quay/issues/164))
### Configvalidation
- [e7fef0e8](https://github.com/quay/quay/commit/e7fef0e80385a6a06a32d3d009e37311936320fa): load only certificates (PROJQUAY-2416) ([#118](https://github.com/quay/quay/issues/118))
### Cors
- [98d89a1f](https://github.com/quay/quay/commit/98d89a1fcef2c7ffdec3bfda5ea86f2e9c4261f6): check for request_origin being set (PROJQUAY-5213) ([#1811](https://github.com/quay/quay/issues/1811))
- [017c4f0b](https://github.com/quay/quay/commit/017c4f0ba1f28acdb22924f3f660f2dbbe4a98ff): Adding missing method type (PROJQUAY-4800) ([#1651](https://github.com/quay/quay/issues/1651))
### Data
- [a4ed9866](https://github.com/quay/quay/commit/a4ed9866089b43de9dbc3947fc5b340d5e71bc82): increase max len for proxy cache config credentials ([#1241](https://github.com/quay/quay/issues/1241))
### Data.Secscan_model
- [26dcf458](https://github.com/quay/quay/commit/26dcf45802183bbf696d44b15b6ab5ff44768fcb): canonicalize before comparing
### Data/Buildlogs
- [e1ae52ee](https://github.com/quay/quay/commit/e1ae52ee23deec4ccaf76e2f3ef04f7e79a6fa4c): format file with black ([#1061](https://github.com/quay/quay/issues/1061))
### Database
- [24b3c153](https://github.com/quay/quay/commit/24b3c15334dd354f16ed79a766dcaba43561cf5a): handle nested transaaction when trying to close before transaction (PROJQUAY-3303) ([#1157](https://github.com/quay/quay/issues/1157))
- [7cdb88b5](https://github.com/quay/quay/commit/7cdb88b5789987c492666de381a666c5afce8ef3): force close existing non-pooled connections before transaction (PROJQUAY-3303) ([#1153](https://github.com/quay/quay/issues/1153))
- [c5608d97](https://github.com/quay/quay/commit/c5608d976511e5645b3c879908d7f839323a83cd): retry connections on stale MySQL connections (PROJQUAY-3303) ([#1148](https://github.com/quay/quay/issues/1148))
### Db
- [eb62f4e9](https://github.com/quay/quay/commit/eb62f4e999768a3a5acc68957e7198435ef432ad): remove url unqoute from migration logic (PROJQUAY-3266) ([#1126](https://github.com/quay/quay/issues/1126))
- [8591caf0](https://github.com/quay/quay/commit/8591caf0372dc0f68eb146a5e28a06eedd3fea87): remove transaction from empty layer upload (PROJQUAY-1946) ([#775](https://github.com/quay/quay/issues/775))
### Debug
- [9c327425](https://github.com/quay/quay/commit/9c32742514129207b95838979a708db9e1b3f48a): Log X-Forwaded-For for requests (PROJQUAY-2883) ([#1027](https://github.com/quay/quay/issues/1027))
- [4a02e1bd](https://github.com/quay/quay/commit/4a02e1bd0955b2cffd1805830274607c9b8c932d): Log X-Forwaded-For for requests (PROJQUAY-2883) ([#1026](https://github.com/quay/quay/issues/1026))
### Defaults
- [a29f3e0e](https://github.com/quay/quay/commit/a29f3e0eea6d475d6f621da19b083876737d5262): Update defaults in config and schema (PROJQUAY-2425) ([#923](https://github.com/quay/quay/issues/923))
- [250e355a](https://github.com/quay/quay/commit/250e355a3004fefaf5136e4a46280d5f9c1902dc): Add defaults for nested repos and init users (PROJQUAY-2425) ([#130](https://github.com/quay/quay/issues/130))
### Dep
- [566d8bae](https://github.com/quay/quay/commit/566d8baefd3cfa078a06c349f65fe63b10fb2a01): updating jinja2 to 3.1.5 (PROJQUAY-8375) ([#3549](https://github.com/quay/quay/issues/3549))
- [a89ec59b](https://github.com/quay/quay/commit/a89ec59ba01e4be6558f003630ace952f6b52f11): updating axios (PROJQUAY-7657) ([#3462](https://github.com/quay/quay/issues/3462)) ([#3504](https://github.com/quay/quay/issues/3504))
### Deploy
- [5f9333ce](https://github.com/quay/quay/commit/5f9333ce08793c186bc1adeee34e8ea3806538fb): use PAT for creating PR on quay repo (PROJQUAY-5048) ([#207](https://github.com/quay/quay/issues/207))
- [d72b1bb3](https://github.com/quay/quay/commit/d72b1bb3dc8b0c01be567417dc004c414db8b74d): Allow for dynamic service names (PROJQUAY-5103) ([#1759](https://github.com/quay/quay/issues/1759))
- [11481cd2](https://github.com/quay/quay/commit/11481cd2f208ff17d14e31c71d10bb63bc6eea89): fix release.yaml quote (PROJQUAY-5048) ([#206](https://github.com/quay/quay/issues/206))
- [28b4036c](https://github.com/quay/quay/commit/28b4036cae86184ff079fb1c8823f6e400809d74): Create a PR against quay for every release (PROJQUAY-5048) ([#204](https://github.com/quay/quay/issues/204))
- [aa78a8c8](https://github.com/quay/quay/commit/aa78a8c80faea723cb7503bfbeb0137b47477525): add value for empty annotation (PROJQUAY-3860) ([#1755](https://github.com/quay/quay/issues/1755))
- [58f85e46](https://github.com/quay/quay/commit/58f85e46d95c2e87938c6d1f43c48f32f38d392c): Add workflow to auto release on push (PROJQUAY-5048) ([#200](https://github.com/quay/quay/issues/200))
- [a0ea7d7b](https://github.com/quay/quay/commit/a0ea7d7bf645f20315cbe521fe01f34f58b98086): add annotation for disabling DVO check (PROJQUAY-3680) ([#1753](https://github.com/quay/quay/issues/1753))
- [633cfaec](https://github.com/quay/quay/commit/633cfaec40b1be7ac1f335fef5691e0eef34146d): fix units in slo panel (PROJQUAY-4956) ([#1749](https://github.com/quay/quay/issues/1749))
- [b39876d5](https://github.com/quay/quay/commit/b39876d5e685e2121ca33f307436ad401275cc91): change push-pull panel (PROJQUAY-4956) ([#1735](https://github.com/quay/quay/issues/1735))
- [f3f608f2](https://github.com/quay/quay/commit/f3f608f22c82e0af2aa76ac50bb3fdbde7b9e00e): change slo dashboard (PROJQUAY-5026) ([#1732](https://github.com/quay/quay/issues/1732))
- [ea0f6f02](https://github.com/quay/quay/commit/ea0f6f02488c854512aa57f3e73d7a5b03b5ebed): update slo dashboard (PROJQUAY-4488) ([#1712](https://github.com/quay/quay/issues/1712))
- [b0b35184](https://github.com/quay/quay/commit/b0b35184f94dbe337aa6c54c94c1d07df2f3ef68): add weight to anti-affinity (PROJQUAY-3684) ([#1711](https://github.com/quay/quay/issues/1711))
- [45a40d4d](https://github.com/quay/quay/commit/45a40d4d6a6ee98f07605dc9cc71a238ba059768): add podAntiAffinity to deployment (PROJQUAY-3684) ([#1700](https://github.com/quay/quay/issues/1700))
- [a6177291](https://github.com/quay/quay/commit/a6177291c1ff2af207a6f18812a471133fe3bb16): add panel to dashboard (PROJQUAY-4486) ([#1698](https://github.com/quay/quay/issues/1698))
- [b69f3f36](https://github.com/quay/quay/commit/b69f3f36af0f3a7f80e57cd291b6b523576634ee): fix api panels in dashboard (PROJQUAY-4485) ([#1668](https://github.com/quay/quay/issues/1668))
- [cc5c3c79](https://github.com/quay/quay/commit/cc5c3c7996d9a498d890ea124fffb878551519ba): update grafana dashboard (PROJQUAY-4484) ([#1655](https://github.com/quay/quay/issues/1655))
- [ad4c13d7](https://github.com/quay/quay/commit/ad4c13d713f1022ba571e21580417b23ed86905f): Add deployment manifests for CloudFlare (PROJQUAY-3512) ([#1604](https://github.com/quay/quay/issues/1604))
- [6356fbb1](https://github.com/quay/quay/commit/6356fbb1b9cdddbe1e231d01b196ce7cf926bbb7): Add ignore validation for py3 deployment (PROJQUAY-2542) ([#1121](https://github.com/quay/quay/issues/1121))
- [d43b41c5](https://github.com/quay/quay/commit/d43b41c58a8c53dfc49458e2743fe915725fe269): Add GRPC service for builds (PROJQUAY-3189) ([#1109](https://github.com/quay/quay/issues/1109))
- [293e0619](https://github.com/quay/quay/commit/293e0619de040994331f4437a0b35dac5d10f323): Add LB service with no proxy-protocol (PROJQUAY-2883) ([#1006](https://github.com/quay/quay/issues/1006))
- [1589351b](https://github.com/quay/quay/commit/1589351b7433941411ec4e12d1a3fe9cfdcc5c31): Add clair back fill worker deployment manifests ([#991](https://github.com/quay/quay/issues/991))
- [01d41364](https://github.com/quay/quay/commit/01d4136406e237b32c80d35f6123b2c0b53f5b93): Update syslog image tag(PROJQUAY-2374) ([#966](https://github.com/quay/quay/issues/966))
- [7458578d](https://github.com/quay/quay/commit/7458578d1a5fe669e2d2b4f943360a7acaacac54): Seperate py3 deployment manifests (PROJQUAY-2374) ([#931](https://github.com/quay/quay/issues/931))
- [5a56145b](https://github.com/quay/quay/commit/5a56145ba5d49702430b030b84df8a66426b77c8): Update app-sre build script (PROJQUAY-2374) ([#934](https://github.com/quay/quay/issues/934))
- [6b01bd12](https://github.com/quay/quay/commit/6b01bd124531e428b2ebd99f9f4f59c5907a024c): Push py3 images to a different quay repo (PROJQUAY-2374) ([#930](https://github.com/quay/quay/issues/930))
- [173dfbfc](https://github.com/quay/quay/commit/173dfbfc8adf67286e22e1f5daadf984d5fcbf3d): Update quay deployment manifests for py3 canary (PROJQUAY-2373) ([#902](https://github.com/quay/quay/issues/902))
- [ce3cb357](https://github.com/quay/quay/commit/ce3cb357bd2abb7f1f7ddf6bc21f6b0294d9803e): update component label value for recovery (PROJQUAY-970) ([#832](https://github.com/quay/quay/issues/832))
- [d6616e9e](https://github.com/quay/quay/commit/d6616e9e1f4bcfc28ab80339448787cc19eca8d3): Add recovery endpoint deployment manifests (PROJQUAY-970) ([#831](https://github.com/quay/quay/issues/831))
- [2d7c0e09](https://github.com/quay/quay/commit/2d7c0e09556fec063a27ebda7a9188a3d06dc58c): add prom service for OpenShift
### Deploy/Openshift
- [af868c46](https://github.com/quay/quay/commit/af868c46d0ed0a6d60181be87d056af72b18c0d8): template monitoring resources
### Deployment
- [242d4def](https://github.com/quay/quay/commit/242d4defc7d0a47f932f5338283f088c92cc8dc7): Change canary to blue deployment (PROJQUAY-1896) ([#781](https://github.com/quay/quay/issues/781))
- [080010e8](https://github.com/quay/quay/commit/080010e8cd7f2646c01fe29f17fae502c3114b31): Add image tag param to the deploy file (PROJQUAY-1896) ([#759](https://github.com/quay/quay/issues/759))
- [03c610d5](https://github.com/quay/quay/commit/03c610d51011061dd33499b5c38aacfcadf0f0c6): Add canary deployment to quay-app (PROJQUAY-1896) ([#754](https://github.com/quay/quay/issues/754))
### Deps
- [9510f94a](https://github.com/quay/quay/commit/9510f94a44c2e628369dfc7f7932c7ffe62fdbd2): bump gunicorn (PROJQUAY-8726) ([#3742](https://github.com/quay/quay/issues/3742))
- [89cae83f](https://github.com/quay/quay/commit/89cae83fa31e2abb87b2a7dc1563b7cfdf0be3b4): updating jquery to 3.5.0 (PROJQUAY-8522) ([#3640](https://github.com/quay/quay/issues/3640))
- [9a6539dc](https://github.com/quay/quay/commit/9a6539dc9e4c93ecadfcd3b14aade44999be6c77): adding requirements-build.txt ([#3518](https://github.com/quay/quay/issues/3518))
- [617c1fd1](https://github.com/quay/quay/commit/617c1fd10bc75d592e7004dfce30fe54914ce36b): bump protobuf (PROJQUAY-7970) ([#3331](https://github.com/quay/quay/issues/3331)) ([#3487](https://github.com/quay/quay/issues/3487))
- [1375269e](https://github.com/quay/quay/commit/1375269eebd1b407aaeb8bbcb5171eac3a4d7a19): downgrading cryptography ([#3492](https://github.com/quay/quay/issues/3492)) ([#3501](https://github.com/quay/quay/issues/3501))
- [0d813cf3](https://github.com/quay/quay/commit/0d813cf3ad0d6b98662c14d9a33c7342a8487a70): Upgrade cryptography package to 43.0.3 (PROJQUAY-7032) ([#3420](https://github.com/quay/quay/issues/3420)) ([#3485](https://github.com/quay/quay/issues/3485))
- [bb53127d](https://github.com/quay/quay/commit/bb53127d015c6e9c2fee0643281667c539905f4b): upgrade upstream requirements.txt package versions ([#1072](https://github.com/quay/quay/issues/1072))
- [8d9fa22c](https://github.com/quay/quay/commit/8d9fa22c26e5202c1036cf1137de135f2255e7b9): Update boto2 to boto3 ([#479](https://github.com/quay/quay/issues/479))
### Dev
- [d3cc640f](https://github.com/quay/quay/commit/d3cc640fef64d673ae0c8ff9aef84aad13562c45): Update Clair for dev (PROJQUAY-4461) ([#1528](https://github.com/quay/quay/issues/1528))
- [04af141a](https://github.com/quay/quay/commit/04af141a49fa231157d91f20f04ab498e307228d): Add pre-commit script to run black (PROJQUAY-4039) ([#1432](https://github.com/quay/quay/issues/1432))
### Doc
- [7a70a98b](https://github.com/quay/quay/commit/7a70a98b1ea616f79cdd3f691e4d2c55c4be6a7c): Fix broken links in the CHANGELOG (PROJQUAY-2298) ([#858](https://github.com/quay/quay/issues/858))
### Doc 
- [34cd7d09](https://github.com/quay/quay/commit/34cd7d09188cabe90af78ed6ef7b3cb048cfe309): update Instructions for Deploying on OpenShift ([#1537](https://github.com/quay/quay/issues/1537))
### Docker
- [95432674](https://github.com/quay/quay/commit/9543267442c716e862e65d5e68682b349e87d889): s/requirements-test/requirements-dev
### Dockerfile
- [50d2a827](https://github.com/quay/quay/commit/50d2a82783da906a3a68064fe0b9ab10e956f550): ubi8 requires python38, otherwise installs 3.6 by default (PROJQUAY-3148) ([#1092](https://github.com/quay/quay/issues/1092))
- [5267cfe7](https://github.com/quay/quay/commit/5267cfe75189de7df7e61a4daa9ea4570de81cfe): update upstream image to use ubi8 as base (PROJQUAY-3148) ([#1082](https://github.com/quay/quay/issues/1082))
- [085e33be](https://github.com/quay/quay/commit/085e33bed74957fc083a03868bb7bfb1b892dc48): set QUAYRUN in non-standard dockerfiles ([#1013](https://github.com/quay/quay/issues/1013))
- [cdc7b61f](https://github.com/quay/quay/commit/cdc7b61f9e1be90d4dbd621810ea7c30a45bb75a): make sure the production dockerfile doesn't pull from dockerhub ([#929](https://github.com/quay/quay/issues/929))
- [da558b0f](https://github.com/quay/quay/commit/da558b0f68228fad28a7cf3b6019f76dc5355e6d): replace golang base image in production dockerfile ([#928](https://github.com/quay/quay/issues/928))
- [139c9abc](https://github.com/quay/quay/commit/139c9abc66c5f60ec9eaf910057afdb28734413b): use separate dockerfile for production deployment ([#927](https://github.com/quay/quay/issues/927))
- [495dd908](https://github.com/quay/quay/commit/495dd9086ea5ac8bb19b0ac175414df1be85aad3): Update symlink in upstream dockerfile (PROJQUAY-2550) ([#889](https://github.com/quay/quay/issues/889))
- [1f7d128c](https://github.com/quay/quay/commit/1f7d128c8d38db7de7b909a8229102ae982198b1): Fix downstream python site-packages location (PROJQUAY-2258) ([#842](https://github.com/quay/quay/issues/842))
- [6e809033](https://github.com/quay/quay/commit/6e809033736d5d0d5855457675b91eec794fcdaa): Fix QUAYCONF symlink and config-tool build in refactored Dockerfile (PROJQUAY-2254) ([#837](https://github.com/quay/quay/issues/837))
- [86d150a2](https://github.com/quay/quay/commit/86d150a2044a1eb24140b0940ba6f830b05c842b): refactor dockerfile (PROJQUAY-1997) ([#787](https://github.com/quay/quay/issues/787))
- [6267085d](https://github.com/quay/quay/commit/6267085d10dd382c90fe46bea8bad2f1766d5ad5): add pushgateway to OSBS images
### Dockerfile
- [f0f31e0b](https://github.com/quay/quay/commit/f0f31e0b7a864c5322c6d7981d9f4afa4ad8e8e3): use nodejs ubi8 image to build frontends ([#1355](https://github.com/quay/quay/issues/1355))
### Docs
- [589a932b](https://github.com/quay/quay/commit/589a932b50791df416329fe65d456bf2897eda00): Add documentation for TLS usage (PROJQUAY-4558) ([#188](https://github.com/quay/quay/issues/188))
- [31de43f6](https://github.com/quay/quay/commit/31de43f6ccc005e6d5009aefdf935f98fe1834fe): Remove link from example .env file
- [8f64efd6](https://github.com/quay/quay/commit/8f64efd6815a76cd27139da5df16983213c71048): consolidate getting started guides (PROJQUAY-2500) ([#884](https://github.com/quay/quay/issues/884))
- [f59ebb1e](https://github.com/quay/quay/commit/f59ebb1e488d49f76b385d28bf9feed740886caa): add basic prometheus doc
### Documentation
- [ae0bd06d](https://github.com/quay/quay/commit/ae0bd06d1dc1124a6b64460884d369d0af997f4a): Added instructions to setup dev environment (PROJQUAY-2277) ([#844](https://github.com/quay/quay/issues/844)) ([#844](https://github.com/quay/quay/issues/844))
### Editor
- [6f7dea7f](https://github.com/quay/quay/commit/6f7dea7f84faeaf7b07b8cc0c5f5063dcbb4fe13): Bump config tool to v0.1.12 (PROJQUAY-3593) ([#1267](https://github.com/quay/quay/issues/1267))
- [408c0535](https://github.com/quay/quay/commit/408c05355202e5e325190614c76d65421992cdf5): Remove BITTORRENT_FILENAME_PEPPER from generated config
- [fd0a2762](https://github.com/quay/quay/commit/fd0a2762c9d6dfe07877d0d152d9ed378034351b): Remove certs from ui scope on select external-tls (PROJQUAY-2528) ([#127](https://github.com/quay/quay/issues/127))
- [0f77b0b4](https://github.com/quay/quay/commit/0f77b0b41c07c860991f196c0b3cfb525a0894dc): Add logic to allow managing/unmanaging of RepoMirror from ui ([#126](https://github.com/quay/quay/issues/126))
- [ef304b75](https://github.com/quay/quay/commit/ef304b75d280dead30aac42edbe025d6e5aee32b): Add sslmode=verify-full when Postgres cert uploaded (PROJQUAY-2200) ([#111](https://github.com/quay/quay/issues/111))
### Email
- [d81efe2f](https://github.com/quay/quay/commit/d81efe2f3ce545a398a2fba0b4fdc4ac7559376b): fix org recovery link in email (PROJQUAY-2589) ([#903](https://github.com/quay/quay/issues/903))
### Endpoints/V2
- [59875347](https://github.com/quay/quay/commit/59875347186757111a6324d29bc2ea64e0f9d499): handle generic proxy related errors ([#1213](https://github.com/quay/quay/issues/1213))
### Export Compliance
- [adf70956](https://github.com/quay/quay/commit/adf709568eb84a473b2924b1e5adedf457c86813): Fetching quay user data from federated login username (PROJQUAY-0000) ([#1530](https://github.com/quay/quay/issues/1530))
### Feat
- [be1bddfd](https://github.com/quay/quay/commit/be1bddfd6a5bcedec411bb0140c6f153a4d044b3): Allow action logs to be forwarded to Splunk (PROJQUAY-4993) ([#1764](https://github.com/quay/quay/issues/1764))
- [fe4d66b0](https://github.com/quay/quay/commit/fe4d66b03061078547f517340fba044f459abc5e): pull-thru proxy cache ([#1053](https://github.com/quay/quay/issues/1053))
- [fca67e77](https://github.com/quay/quay/commit/fca67e7729d95e8cafee5029ca08f503c803a51e): mypy type annotations (PROJQUAY-740) ([#455](https://github.com/quay/quay/issues/455))
### Fips
- [65363057](https://github.com/quay/quay/commit/653630579f63498670215779ab5cf80d61857253): enforce smtp tls (PROJQUAY-1804) ([#782](https://github.com/quay/quay/issues/782)) ([#782](https://github.com/quay/quay/issues/782))
### Fix
- [c82d78ae](https://github.com/quay/quay/commit/c82d78ae8501b040c7539a3e539aaab0485d1052): Adding default vault to quota parameter (PROJQUAY-0000) ([#1171](https://github.com/quay/quay/issues/1171))
### Fix
- [80cd9c33](https://github.com/quay/quay/commit/80cd9c332492bf29fd8139c8abfeef4c4ff9b6f5): Pass CONTAINER_RUNTIME to quay-builder (PROJQUAY-5910) ([#2105](https://github.com/quay/quay/issues/2105))
- [12e7c8fc](https://github.com/quay/quay/commit/12e7c8fcb0e9c2bcb3b839a21b9dbe4e4025c683): support oci image indexes that don't specify a mediaType (PROJQUAY-4254) ([#1469](https://github.com/quay/quay/issues/1469))
- [f2c4375f](https://github.com/quay/quay/commit/f2c4375f657a39a141ae0ed540659b1c50baeb93): enable non-admins to cache images via pull-thru (PROJQUAY-3806) ([#1366](https://github.com/quay/quay/issues/1366))
- [d3809b2e](https://github.com/quay/quay/commit/d3809b2e36a926721119726070d465c875110085): pin setuptools to version 57 ([#885](https://github.com/quay/quay/issues/885))
- [23b8a239](https://github.com/quay/quay/commit/23b8a23993fcc29d7c1d9440c4b4045366b80c99): Use Python 3.8 for CI tests ([#580](https://github.com/quay/quay/issues/580))
- [4672db1d](https://github.com/quay/quay/commit/4672db1df76874238baf134d04e74112ac9f630d): Missing storage argument and type error when calling file.write ([#514](https://github.com/quay/quay/issues/514))
### Format
- [ef91c57c](https://github.com/quay/quay/commit/ef91c57c233e9d23372afac34c0d062a38171ffa): Updating black to resolve click dependency issue (PROJQUAY-3487) ([#1209](https://github.com/quay/quay/issues/1209))
- [0722e6ee](https://github.com/quay/quay/commit/0722e6ee5e3ace5f88adbc69899b9fba6d9550e2): remove extra comma from s3 connect_kwargs ([#709](https://github.com/quay/quay/issues/709))
### Formatting
- [e4390472](https://github.com/quay/quay/commit/e4390472a47368a42f2fec8c6cef8c428d0ef980): Update code to obey the linter (PROJQUAY-0) ([#1057](https://github.com/quay/quay/issues/1057))
### Frontend
- [a24d8708](https://github.com/quay/quay/commit/a24d870839f27e6138dfdc1703ea36b49226db2e): Set default USERFILES_LOCATION to a valid storage
### GUI
- [020b3abe](https://github.com/quay/quay/commit/020b3abea2f8be15568f2e4e7f5de125e8c23298): Show how to pull an image using podman pull ([#1332](https://github.com/quay/quay/issues/1332))
### Gc
- [563d04aa](https://github.com/quay/quay/commit/563d04aa00dce607af8671c2a7fa9599b279478c): remove orphaned storage on repository purge (PROJQUAY-2313) ([#961](https://github.com/quay/quay/issues/961))
- [efa0692e](https://github.com/quay/quay/commit/efa0692e5ac3c47719dc8940d65feaa5f26a568b): increment quay_gc_repos_purged for NamespaceGCWorker (PROJQUAY-1802) ([#749](https://github.com/quay/quay/issues/749))
- [f774e4c6](https://github.com/quay/quay/commit/f774e4c6b6c674c822057a1d3dd49a3d5c36e6ca): add metrics for deleted resources ([#711](https://github.com/quay/quay/issues/711))
- [3b94cda7](https://github.com/quay/quay/commit/3b94cda75180d1355046ed656490aa45f63ee479): fix GlobalLock ttl unit and increase gc workers lock timeout ([#712](https://github.com/quay/quay/issues/712))
### Geo-Rep
- [0e08328b](https://github.com/quay/quay/commit/0e08328b1d4ca9a7361aade8a1e190f99cbc4223): Initialize features from config in util script (PROJQUAY-5627) ([#1967](https://github.com/quay/quay/issues/1967))
- [95819675](https://github.com/quay/quay/commit/958196757f63b70391562b09e922959a04c35c84): Add util script to remove geo-rep location and corresponding image locations (PROJQUAY-4995) ([#1943](https://github.com/quay/quay/issues/1943))
### Georep
- [b5b7aabe](https://github.com/quay/quay/commit/b5b7aabefa4b261e40b840fe7836b5c08bad544e): Add error handling for remove location script (PROJQUAY-5878) ([#2094](https://github.com/quay/quay/issues/2094))
### Go
- [372289ad](https://github.com/quay/quay/commit/372289ada43db9cf3e2fd10eca3f482b14677c3a): Update golang to version 1.16 (PROJQUAY-1605) ([#176](https://github.com/quay/quay/issues/176))
### Healthcheck
- [2dd0d3e2](https://github.com/quay/quay/commit/2dd0d3e248d5dc23097f65a283661ef5972edd05): fix invalid Exception attribute (PROJQUAY-5047) ([#1782](https://github.com/quay/quay/issues/1782))
- [c36945b8](https://github.com/quay/quay/commit/c36945b8361caf65ba294bc56722b5c6296b5035): Use db_kwargs in health check (PROJQUAY-4222) ([#1507](https://github.com/quay/quay/issues/1507))
### Href
- [0d37fb03](https://github.com/quay/quay/commit/0d37fb03055ba891dc89ede742c9fd5becb49c7f): Fix broken link (PROJQUAY-2449) ([#114](https://github.com/quay/quay/issues/114))
### Imagemirror
- [0d3ecb13](https://github.com/quay/quay/commit/0d3ecb132e8afe6eb4184948e05a9717759b70c3): Add unsigned registries mirror option (PROJQUAY-3106) ([#1085](https://github.com/quay/quay/issues/1085))
### Init
- [e1745a9b](https://github.com/quay/quay/commit/e1745a9b13dcb0648091fa61a96cb076750d6590): fix bash path before appending certs (PROJQUAY-3881) ([#1359](https://github.com/quay/quay/issues/1359))
- [8786ef2e](https://github.com/quay/quay/commit/8786ef2efd78baee88d2354279fe9499f552873a): ensure a newline is present before appending certs (PROJQUAY-3881) ([#1356](https://github.com/quay/quay/issues/1356))
- [16d9a2ce](https://github.com/quay/quay/commit/16d9a2ce41f2990911c7e18d8b41a6e1e3b41ae0): ensure a newline is present before appending certs (PROJQUAY-3881) ([#1352](https://github.com/quay/quay/issues/1352))
- [c06ca373](https://github.com/quay/quay/commit/c06ca373229a7743570a917595c7912c6f23769a): github workflows
### Invoice
- [5a1fa17a](https://github.com/quay/quay/commit/5a1fa17a799800f09a9bf447a5c83e3b01bd3ef1): update invoice template to fix layout (PROJQUAY-3267) ([#1182](https://github.com/quay/quay/issues/1182))
### Ipresolver
- [b9557d14](https://github.com/quay/quay/commit/b9557d1486e9a70c0659d8d6d94bae4d053c4eb6): update country mmdb (PROJQUAY-3031) ([#1049](https://github.com/quay/quay/issues/1049))
### Json Loads Fix
- [0c65f88a](https://github.com/quay/quay/commit/0c65f88a0ec5e3b847f45c1fdc0e53365126c22a): given arg should be a str ([#527](https://github.com/quay/quay/issues/527))
### Keystonev2
- [4c429687](https://github.com/quay/quay/commit/4c429687fe4a6c813e0d8092794037d0322bb8d3): populate user.name into UserInformation ([#440](https://github.com/quay/quay/issues/440))
### Ldap
- [b2a5b3ab](https://github.com/quay/quay/commit/b2a5b3abb73fd7846a3d8061a02b71c76133ce50): Don't convert dashes to underscores in usernames (PROJQUAY-5253) ([#1808](https://github.com/quay/quay/issues/1808))
- [c8a7e641](https://github.com/quay/quay/commit/c8a7e6412aecd3a732aaf9681398c2fe1aa1b382): add test for user filter (PROJQUAY-2766) ([#980](https://github.com/quay/quay/issues/980))
- [acc37482](https://github.com/quay/quay/commit/acc3748236b3123fa3ab55faf1d5061eb5d4293c): Remove validation check for users (PROJQUAY-2343) ([#142](https://github.com/quay/quay/issues/142))
### Local-Dev
- [eea5cfcb](https://github.com/quay/quay/commit/eea5cfcb2bc7099f40d5758e360d16f49492d841): Increase timeout for gunicorn tasks to come up (PROJQUAY-2114) ([#808](https://github.com/quay/quay/issues/808))
- [113ccebb](https://github.com/quay/quay/commit/113ccebbbfea827e959630be312ef8347e7a7c48): implement local development environment ([#610](https://github.com/quay/quay/issues/610))
### Lock
- [c12654bf](https://github.com/quay/quay/commit/c12654bf46da701cd30dd9995091444bc046cf69): allows global lock to be used from main app (PROJQUAY-788) ([#745](https://github.com/quay/quay/issues/745))
- [778afaf3](https://github.com/quay/quay/commit/778afaf36be17d54958d5fa5bd8f365bea3ee965): reuse redis client when creating locks (PROJQUAY-1872) ([#741](https://github.com/quay/quay/issues/741))
### Locking
- [780bca5e](https://github.com/quay/quay/commit/780bca5eeb4b72ba1517134874fc853d7045f381): change log severity (PROJQUAY-5221) ([#1820](https://github.com/quay/quay/issues/1820))
### Login
- [c5ea9fa1](https://github.com/quay/quay/commit/c5ea9fa16924b865822f902811e3d10d74743047): Use dedicated mailing list for export compliance email (PROJQUAY-4844) ([#1730](https://github.com/quay/quay/issues/1730))
- [68844dbf](https://github.com/quay/quay/commit/68844dbf5e6fbfe814b0c917a3026efc3f982639): Re-raise the export compliance exception on RHSSO (prod) (PROJQUAY-4844) ([#1726](https://github.com/quay/quay/issues/1726))
- [f2b70c50](https://github.com/quay/quay/commit/f2b70c50316c8c6fe24496e1060b8327006aed9f): Re-raise the export compliance exception on RHSSO (PROJQUAY-4844) ([#1725](https://github.com/quay/quay/issues/1725))
- [cb590f9a](https://github.com/quay/quay/commit/cb590f9a636ccc09daf8a62479c646a2c1246c9d): Add error message for exprot compliance hold (PROJQUAY-4844) ([#1715](https://github.com/quay/quay/issues/1715))
- [442bb168](https://github.com/quay/quay/commit/442bb1689dc42b919b6472e65a31ef8346c9cf1c): Use the correct username for export compliance (PROJQUAY-4844) ([#1696](https://github.com/quay/quay/issues/1696))
- [5bd24264](https://github.com/quay/quay/commit/5bd2426400d46f350b97755974cdc2e9dfc4588b): Add subject in debug logs for export compliance (PROJQUAY-4844) ([#1695](https://github.com/quay/quay/issues/1695))
### Logs
- [0c2f4c92](https://github.com/quay/quay/commit/0c2f4c9224e7d72fcf978c0f51bfaa44a9359319): Add autologin to splunk's connect() to allow retries (PROJQUAY-5621) ([#1957](https://github.com/quay/quay/issues/1957))
- [171f9cc1](https://github.com/quay/quay/commit/171f9cc14c182bd4d928964cbcea1504b2cc9449): ssl_ca_path should be optional (PROJQUAY-4993) ([#1920](https://github.com/quay/quay/issues/1920))
- [490a6b2c](https://github.com/quay/quay/commit/490a6b2ce8d4fd24147f39a04ca8339a94772cce): Add SSL cert support and test coverage for splunk logging (PROJQUAY-4993) ([#1878](https://github.com/quay/quay/issues/1878))
- [41cd8330](https://github.com/quay/quay/commit/41cd8330d0e7be8941776dc4e06957017f5fa605): add audit log events for login/logout to Quay (PROJQUAY-2344) ([#1866](https://github.com/quay/quay/issues/1866))
- [37e4990b](https://github.com/quay/quay/commit/37e4990b075ab7268d2707e032f4022093b1e76d): Add audit logs for organization and user namespace activities (PROJQUAY-3482) ([#1846](https://github.com/quay/quay/issues/1846))
- [ed86a102](https://github.com/quay/quay/commit/ed86a102ce0c619033714e0afe30a71a331465f4): validate date range is within configuration (PROJQUAY-4959) ([#1707](https://github.com/quay/quay/issues/1707))
- [1bd016fd](https://github.com/quay/quay/commit/1bd016fda56c1a7bd0940e6a204476c5777198b7): Add repository information for build audit logs (PROJQUAY-4726) ([#1705](https://github.com/quay/quay/issues/1705))
- [33451ca9](https://github.com/quay/quay/commit/33451ca96e3996a7107d8645dcdec178cda420cc): audit logs on manual build triggers and build cancellations (PROJQUAY-4726) ([#1682](https://github.com/quay/quay/issues/1682))
- [fe2b89d6](https://github.com/quay/quay/commit/fe2b89d6563df35dbe8c6cb891d7cd9f5d90df8d): create action logs on proxy cache config creation/deletion (PROJQUAY-4718) ([#1625](https://github.com/quay/quay/issues/1625))
### Makefile
- [692e3cee](https://github.com/quay/quay/commit/692e3cee29132af1035ba66fa32404f0f9e2e857): use non-standard port for postgres test container ([#1485](https://github.com/quay/quay/issues/1485))
- [fd4e7723](https://github.com/quay/quay/commit/fd4e7723f34f11d085cb7951c6eab084efe39d65): use variable to tell postgres test target which tests to run ([#1475](https://github.com/quay/quay/issues/1475))
### Makefile
- [10e88d29](https://github.com/quay/quay/commit/10e88d29aa518c53da33da800309cdd3310925a4): Add local-dev-build-frontend step (PROJQUAY-2693) ([#933](https://github.com/quay/quay/issues/933))
- [e529ef93](https://github.com/quay/quay/commit/e529ef934d53cb4aae35a3281cd812002acc6606): remove extraneous requirements-dev
### Marketplace
- [de8c48fa](https://github.com/quay/quay/commit/de8c48fa28130f425acc962b739b7ced9a667009): fixing allowed repo count (PROJQUAY-5513) ([#1891](https://github.com/quay/quay/issues/1891))
- [c3539469](https://github.com/quay/quay/commit/c3539469105386150fad2e2163e8afefb3fd26d3): fix path to api cert (PROJQUAY-5409) ([#1870](https://github.com/quay/quay/issues/1870))
- [0a1c7fb2](https://github.com/quay/quay/commit/0a1c7fb22e0ff1261bb49f1c4dc12125d78c2f6d): add reconciler (PROJQUAY-5320) ([#1817](https://github.com/quay/quay/issues/1817))
### Merge Branch 'FileUploads' Of Https
- [d9dbde22](https://github.com/quay/quay/commit/d9dbde226d12736bcd8b97cf5724bd7f993a60ee): //github.com/quay/config-tool into fileUploads
- [3680dc27](https://github.com/quay/quay/commit/3680dc2798139f03ba205f524d0f81b078706b94): //github.com/quay/config-tool into fileUploads
- [98671957](https://github.com/quay/quay/commit/986719579ccd98710c0c282d26185d88ec4a0e6c): //github.com/quay/config-tool into fileUploads
- [c0e31276](https://github.com/quay/quay/commit/c0e312760248a6adf570b1774d1bbd8276635807): //github.com/quay/config-tool into fileUploads
### Merge Branch 'Master' Of Github.Com
- [0b3e2402](https://github.com/quay/quay/commit/0b3e240243d47db799a00fb0428e50bf83357c92): quay/config-tool
### Merge Branch 'Master' Of Https
- [276308dd](https://github.com/quay/quay/commit/276308ddcfe4f516db1013c137a7cc3ae1911ece): //github.com/quay/config-tool
- [dce89b56](https://github.com/quay/quay/commit/dce89b5642172325e39bbe3c225949906975aafd): //github.com/quay/config-tool
- [adedb28a](https://github.com/quay/quay/commit/adedb28ab7fc0e3da59cc25c87413c32dc63f3dd): //github.com/quay/config-tool
### Metrics
- [6137546f](https://github.com/quay/quay/commit/6137546f3c5743d872aed709f33e7f6018697ac9): s/endpoint/route
- [2e3424d6](https://github.com/quay/quay/commit/2e3424d62320243e9137dc8243009032bbed1b39): push/pull bytes metrics named consistent
- [e8a1f74e](https://github.com/quay/quay/commit/e8a1f74ed33b56f879bfb1a1c6d68ab54bf1bd4c): add debug logging for pushgateway
### Migration
- [08201dea](https://github.com/quay/quay/commit/08201deaec55fc358e3a395b58ab00c9ee408f4c): skip existing mediatype inserts (PROJQUAY-2811) ([#976](https://github.com/quay/quay/issues/976))
- [712b8d74](https://github.com/quay/quay/commit/712b8d749333e9879d15ecf724d335662ddb7af1): configure logging in alembic's env.py (PROJQUAY-2412) ([#875](https://github.com/quay/quay/issues/875))
- [94ed4716](https://github.com/quay/quay/commit/94ed47164bad3ec3b94fa17546bb6d605ec9f188): Add composite index in manifestblob (PROJQUAY-1922) ([#769](https://github.com/quay/quay/issues/769))
### Mirror
- [679380b9](https://github.com/quay/quay/commit/679380b99f67ad852db522360df6eadf3296c38b): Rollback failed tags (PROJQUAY-4322) ([#1496](https://github.com/quay/quay/issues/1496))
- [30298699](https://github.com/quay/quay/commit/30298699fc45b8d713c5ba70a49495c0037d96b2): Default mirror rollback to false (PROJQUAY-4296) ([#1490](https://github.com/quay/quay/issues/1490))
- [14c8d139](https://github.com/quay/quay/commit/14c8d13984ff2e1c8be0357592d942740ef51090): Pass command output to a tempfile instead of pipe (PROJQUAY-3145) ([#1417](https://github.com/quay/quay/issues/1417))
- [d2e758da](https://github.com/quay/quay/commit/d2e758dad5a6c01f88e257885f07a4e51f66712a): Get all tags during rollback (PROJQUAY-3146) ([#1244](https://github.com/quay/quay/issues/1244))
- [f3a8b74d](https://github.com/quay/quay/commit/f3a8b74dafb0633b6539d1187b85923a1079ea4e): increased registry user/pass max length (PROJQUAY-2712) ([#945](https://github.com/quay/quay/issues/945))
- [95ec9478](https://github.com/quay/quay/commit/95ec9478fc6b66f8b87ddcb699c6496f1661c15c): Do not store signatures on repo mirroring (PROJQUAY-2167) ([#816](https://github.com/quay/quay/issues/816))
### Mirroring
- [26a334f5](https://github.com/quay/quay/commit/26a334f5d8bc82ebfcae12081818979865b45409): fix mirror claims for multiple processes (PROJQUAY-3982) ([#1433](https://github.com/quay/quay/issues/1433))
### Modelcache
- [b33f125c](https://github.com/quay/quay/commit/b33f125c58cadfa0342ad1767517077b1c62a664): Add read and write endpoints to Redis (PROJQUAY-1939) ([#795](https://github.com/quay/quay/issues/795))
- [df4ad945](https://github.com/quay/quay/commit/df4ad9452757dd01fb651e2836abcb4620df9db7): Make ModelCache TTL configurable (PROJQUAY-1878) ([#765](https://github.com/quay/quay/issues/765))
### Namespacequota
- [61f4bd42](https://github.com/quay/quay/commit/61f4bd4252e5780ef1d1a699bc142bb665586014): return 0 when namespace has no size yet ([#1237](https://github.com/quay/quay/issues/1237))
### Nginix
- [2a38784a](https://github.com/quay/quay/commit/2a38784a689434bd9484cb35cdc49f12dbcc0341): update rate limit values for quay based on traffic (PROJQUAY-3283) ([#1175](https://github.com/quay/quay/issues/1175))
### Nginx
- [056b6fca](https://github.com/quay/quay/commit/056b6fca306dc7cbc2a16bc55e92703e195dba43): Minor update to fix toggling issue on Safari (PROJQUAY-4527) ([#1670](https://github.com/quay/quay/issues/1670))
### Nginx
- [30bf4050](https://github.com/quay/quay/commit/30bf40506909db74cedb52212897074ad7228589): mark beginning of string in location match ([#1546](https://github.com/quay/quay/issues/1546))
- [aa7068a2](https://github.com/quay/quay/commit/aa7068a2cc32169c92fb2838951c8067714a6136): block v1/tag for helium miner curl calls (PROJQUAY-3594) ([#1248](https://github.com/quay/quay/issues/1248))
- [7b44f8c0](https://github.com/quay/quay/commit/7b44f8c0d0729515a95ab243e852975e78c0b4fc): Update rate limiting for tags API (PROJQUAY-3283) ([#1233](https://github.com/quay/quay/issues/1233))
- [de0d9764](https://github.com/quay/quay/commit/de0d97640f0e471ae56ded9446d36116513e920f): Increase body timeout for buildman (PROJQUAY-3406) ([#1198](https://github.com/quay/quay/issues/1198))
- [ec7b7610](https://github.com/quay/quay/commit/ec7b7610acff9d585053491eb902032dfc835389): add missing semicolon in template (PROJQUAY-2883) ([#1020](https://github.com/quay/quay/issues/1020))
- [03a36256](https://github.com/quay/quay/commit/03a3625650d4e5aa92aafc5325eefc9712443972): rename base http template file ((PROJQUAY-2883) ([#1007](https://github.com/quay/quay/issues/1007))
- [1ba53f4f](https://github.com/quay/quay/commit/1ba53f4f09a46586f970735250f8d9570732c736): support client ip through x-forwarded-for header (PROJQUAY-2883) ([#1003](https://github.com/quay/quay/issues/1003))
- [630d6f46](https://github.com/quay/quay/commit/630d6f4605124de2a799f17447bab097fff67398): use bigger http/2 chunks for blobs ([#630](https://github.com/quay/quay/issues/630))
### Notification
- [3739c1fc](https://github.com/quay/quay/commit/3739c1fc21223df260874aa4793b6c2b10343e7b): fix user ref when creating notification for quota (PROJQUAY-3711) ([#1288](https://github.com/quay/quay/issues/1288))
- [a126ad06](https://github.com/quay/quay/commit/a126ad06d5a48f54188f32d0aa17ad8172aba8fc): check certs exists for webhooks (PROJQUAY-2424) ([#886](https://github.com/quay/quay/issues/886))
### Notifications
- [0a9487f8](https://github.com/quay/quay/commit/0a9487f8ac358b26aa12bb9851cb61c5786ac4dc): add incoming jwt verification ([#568](https://github.com/quay/quay/issues/568))
### Oauth
- [5f49ffc2](https://github.com/quay/quay/commit/5f49ffc2d0658a70d1784b7bac7cb98dfcf77166): fix oauth token generation when using dangerous scopes (PROJQUAY-4042) ([#1457](https://github.com/quay/quay/issues/1457))
- [922a82a3](https://github.com/quay/quay/commit/922a82a3d945002dd2d259d2d7950614249ef382): Add the code param to the oauthrize.html template (PROJQUAY-3648) ([#1362](https://github.com/quay/quay/issues/1362))
- [7f23e584](https://github.com/quay/quay/commit/7f23e584d12f095e4a67e4d7fcd4fbb36693d1cc): add timeout to OAuth token exchange (PROJQUAY-1335) ([#735](https://github.com/quay/quay/issues/735))
### Oci
- [f50f37a3](https://github.com/quay/quay/commit/f50f37a393fa2273234f8ac0aa9f34a03a77a731): Accept the stricter oci layer type used by default in Helm 3.7 (PROJQUAY-2653) ([#922](https://github.com/quay/quay/issues/922))
- [1994f2d1](https://github.com/quay/quay/commit/1994f2d108a30b6d64a1f491f2f6342604758dc9): add support for zstd compression (PROJQUAY-1417) ([#801](https://github.com/quay/quay/issues/801))
- [64bc11fe](https://github.com/quay/quay/commit/64bc11fe46acdc20795f9a51ba2c8c6926579f77): allow oci artifact registration (PROJQUAY-1032) ([#803](https://github.com/quay/quay/issues/803))
### Oci/Index.Py
- [e262f062](https://github.com/quay/quay/commit/e262f062b7155a0d35a442ddfc2b3340f0f0bbe5): support docker schema2 sub-manifest types ([#1649](https://github.com/quay/quay/issues/1649))
### Openshift
- [ba3d0bd6](https://github.com/quay/quay/commit/ba3d0bd636f1525387c8ed619196a0224b25aff9): use one template for all of quay
### Organization
- [6ba0e881](https://github.com/quay/quay/commit/6ba0e88128b75bc79ca4763d931d2c2be472f8cb): config to allow organization creation on push (PROJQUAY-928) ([#799](https://github.com/quay/quay/issues/799))
### PROJQUAY-1020 Chore
- [f9249d8b](https://github.com/quay/quay/commit/f9249d8baaf4ead12a897443f72f9c8a455de4e7): Fix cdnjs download failure(403) by setting custom User-Agent req header ([#535](https://github.com/quay/quay/issues/535))
### PROJQUAY-138
- [c90cd5d0](https://github.com/quay/quay/commit/c90cd5d09e731746afcc2ef4f0bccbbcb3bf38a1): Enable proxy protocol for Quay application ELB
### PROJQUAY-181
- [56a3bc44](https://github.com/quay/quay/commit/56a3bc443f76a5228ee7296f0a60e99555d097e2): updated nginx to redirect http to https for quay.io
- [72dff0ef](https://github.com/quay/quay/commit/72dff0ef21e8317bd60f8ef5838f38c232fe91fa): redirect http to https for quay.io
### PROJQUAY-3750
- [ac6a8d2f](https://github.com/quay/quay/commit/ac6a8d2f8b93bcff032d3b2dfc57e07432a96709): support registries that do not return a digest header ([#1310](https://github.com/quay/quay/issues/1310))
### PROJQUAY-963
- [d575f391](https://github.com/quay/quay/commit/d575f39136c89c154de8db01be1216dafadb4b20): Add package and vulnerability related metadata into secscan response ([#515](https://github.com/quay/quay/issues/515))
### Permissions
- [16e53211](https://github.com/quay/quay/commit/16e53211082e007f7704abe7f8f0df9d8f8a8b2b): lazy-load superuser permissions (PROJQUAY-5117) ([#1761](https://github.com/quay/quay/issues/1761))
### Pg
- [133437f2](https://github.com/quay/quay/commit/133437f23146f707058c902dad3150218e4850e6): Add warning log when Postgres version less than 13 ([#218](https://github.com/quay/quay/issues/218))
### Proxy
- [ba29a40b](https://github.com/quay/quay/commit/ba29a40b80f637aecabb264062488b63c5157bc4): allowing expiring tags with timemachine set to 0 (PROJQUAY-5558) ([#1907](https://github.com/quay/quay/issues/1907))
- [e349762d](https://github.com/quay/quay/commit/e349762d780c67803e8e2e740178fda7db0b6656): Allow anonymous pulls from registries (PROJQUAY-5273) ([#1906](https://github.com/quay/quay/issues/1906))
- [1342a17b](https://github.com/quay/quay/commit/1342a17b63f3c9f27c09d294923f4499939e7ba7): make upstream related error message more actionable ([#1240](https://github.com/quay/quay/issues/1240))
- [b941a038](https://github.com/quay/quay/commit/b941a0384c19f94cbb8a5a7ef1e1086533ab1b07): raise UpstreamRegistryError if we can't request upstream ([#1220](https://github.com/quay/quay/issues/1220))
- [f248d885](https://github.com/quay/quay/commit/f248d885aab2d95c25c14e73774a8e1940855bc7): don't store entire blob in memory when caching ([#1200](https://github.com/quay/quay/issues/1200))
### Proxy Cache
- [7524171a](https://github.com/quay/quay/commit/7524171ac8fa1db2a450b96dd2b4240f1512afc5): Interface and UI for Proxy cache Configuration (PROJQUAY-3029) ([#1204](https://github.com/quay/quay/issues/1204))
### Proxy Cache
- [342a50eb](https://github.com/quay/quay/commit/342a50eb1f9c7a12a2afdeff6762939069c82def): respect CREATE_PRIVATE_REPO_ON_PUSH flag (PROJQUAY-3743) ([#1426](https://github.com/quay/quay/issues/1426))
- [a4c8924f](https://github.com/quay/quay/commit/a4c8924f11d66a34ce3d178d5ed34332cfb3c3a2): Elaborate hint message for anonymous pulls and making a safe request (PROJQUAY - 0000) ([#1222](https://github.com/quay/quay/issues/1222))
### Pull-Thru
- [d029a465](https://github.com/quay/quay/commit/d029a4652deb763105af0db9ffa05cbf2b6b2343): bump expiration of all parent manifest lists on pull ([#1336](https://github.com/quay/quay/issues/1336))
### Pylint
- [2c239622](https://github.com/quay/quay/commit/2c239622308bc8f92be1a3d06051b6b9587b7e01): drop 2 space ident configuration
### Python
- [2d0adf0c](https://github.com/quay/quay/commit/2d0adf0c189dc446c79ffcb2cdae493307f0d4b2): bump pillow to 8.3.1 (PROJQUAY-2250) ([#852](https://github.com/quay/quay/issues/852))
### Quay
- [dcf5a377](https://github.com/quay/quay/commit/dcf5a377a93c2d16bd2400747106adfd88a25982): Cloudfront multi domain (PROJQUAY-4506) ([#1598](https://github.com/quay/quay/issues/1598))
- [7c566ad4](https://github.com/quay/quay/commit/7c566ad4f3879e08ed82955a14122cd2a2e1f269): Exporting image.oci package to Quay module (PROJQUAY-0000) ([#1548](https://github.com/quay/quay/issues/1548))
- [162b79ec](https://github.com/quay/quay/commit/162b79ec53b1a38ac4dbbb7e00224a308f7ba3c7): Fixing reclassified CVE ratings source (PROJQUAY-2691) ([#937](https://github.com/quay/quay/issues/937))
### Quay UI
- [3a90e1b4](https://github.com/quay/quay/commit/3a90e1b433111224b151932c3403af08e3b1bbad): Creating new username for accounts that login via SSO (PROJQUAY-5289) ([#1831](https://github.com/quay/quay/issues/1831))
- [51c67513](https://github.com/quay/quay/commit/51c675139defa49c17c7847e89889af4d783cf4f): Converting to nearest integer (PROJQUAY-3602) ([#1285](https://github.com/quay/quay/issues/1285))
### Quay-Entrypoint.Sh
- [2735d348](https://github.com/quay/quay/commit/2735d348acff0f7dc849f85f03b675725cd8cfd5): fix openssl commandline ([#264](https://github.com/quay/quay/issues/264))
- [091bbe3e](https://github.com/quay/quay/commit/091bbe3e89f4ed1267d0e91412042170b563201c): don't use scl shells ([#233](https://github.com/quay/quay/issues/233))
### Quay-Entypoint.Sh
- [f89b946c](https://github.com/quay/quay/commit/f89b946ceab7e0636be93927f78b736bd05aa930): fix config argument handling ([#231](https://github.com/quay/quay/issues/231))
### Quay.Io
- [5debec58](https://github.com/quay/quay/commit/5debec58f97ea435ff0826c56202f31bef8c318f): Catching requests from impersonated principals ([#869](https://github.com/quay/quay/issues/869))
### Quay.Io UI
- [20aef6a5](https://github.com/quay/quay/commit/20aef6a589c06d980f24eb866f2328f99b3b2623): Fetching severity from cvss score and removing visibility… ([#887](https://github.com/quay/quay/issues/887))
### Quayio
- [b49fd45e](https://github.com/quay/quay/commit/b49fd45ee646d53c0789d79c60c87a7fb5ae8ec8): Redirect user to billing page when starting free trial (PROJQUAY-4130) ([#1439](https://github.com/quay/quay/issues/1439))
- [247fec3b](https://github.com/quay/quay/commit/247fec3b0511eef3f5dc58633051a5dab4bc0f2e): Add export compliance service to Red Hat SSO (PROJQUAY-2056) ([#1239](https://github.com/quay/quay/issues/1239))
- [34cf5b92](https://github.com/quay/quay/commit/34cf5b922692ce1d122e9a9f920950e7782a37cd): allow migration to skip adding manifest columns if exists (PROJQUAY-2579) ([#901](https://github.com/quay/quay/issues/901))
### Queueworker
- [90f9ef95](https://github.com/quay/quay/commit/90f9ef95af98c7177566abf41213b22839e7206b): prevent stop event on WorkerSleepException (PROJQUAY-1857) ([#737](https://github.com/quay/quay/issues/737))
### Quota
- [f90e5e3d](https://github.com/quay/quay/commit/f90e5e3dcef4bb312e31aaf5a4ce536e81e3e424): Configuring Quota for user panel(PROJQUAY-3767) ([#1334](https://github.com/quay/quay/issues/1334))
- [1e4871ec](https://github.com/quay/quay/commit/1e4871eca27ea1878937a49fb2974401c5963512): Add Cache To Tag Delete (PROJQUAY-3828) ([#1345](https://github.com/quay/quay/issues/1345))
- [f4093b0d](https://github.com/quay/quay/commit/f4093b0db58fbe4dc4663a948e61d3af09f24653): fix caching (PROJQUAY-3660) ([#1291](https://github.com/quay/quay/issues/1291))
- [1e65bff9](https://github.com/quay/quay/commit/1e65bff9fc7b543b03efe3a665a1c74147b83d43): Raising exception when entered quota size is too big (PROJQUAY-3702) ([#1290](https://github.com/quay/quay/issues/1290))
- [5bb2c121](https://github.com/quay/quay/commit/5bb2c121b1466ccd909ffd746cfe1bc185437f8e): Show a different error message if default quota is set on removing quota (PROJQUAY-3657) ([#1287](https://github.com/quay/quay/issues/1287))
- [eea7389a](https://github.com/quay/quay/commit/eea7389a244d26b54a38d876ce3dd949445f1390): Show system default on UI when quota configuration for the org is not set (PROJQUAY-3518) ([#1280](https://github.com/quay/quay/issues/1280))
### Quota
- [a4a23414](https://github.com/quay/quay/commit/a4a23414f83a6878cce866686e9fcaf48b56dc8e): prevent tag creation on rejected manifest (PROJQUAY-3906) ([#2282](https://github.com/quay/quay/issues/2282))
- [6cf0a353](https://github.com/quay/quay/commit/6cf0a3531b7e5538266d11b12a158b8b11d12f67): calculating registry size (PROJQUAY-5476) ([#1879](https://github.com/quay/quay/issues/1879))
- [cf509011](https://github.com/quay/quay/commit/cf50901159c5d232bc61c6c3ff142668a9d92651): moving resetting of child manifest temporary tags to delete endpoint (PROJQUAY-5512) ([#1894](https://github.com/quay/quay/issues/1894))
- [e6f2dc33](https://github.com/quay/quay/commit/e6f2dc3354de47d4f3542e77c1b91be6a144dc7b): excluding robots from quota total (PROJQUAY-5469) ([#1871](https://github.com/quay/quay/issues/1871))
- [a2c379d4](https://github.com/quay/quay/commit/a2c379d47c905e5e6649d3a68bd39459e559df58): Include blob deduplication in totals (PROJQUAY-3942) ([#1751](https://github.com/quay/quay/issues/1751))
- [a0df8950](https://github.com/quay/quay/commit/a0df895005bcd3e53847046f69f6a7add87c88fd): Fix calculating org size (PROJQUAY-3889) ([#1391](https://github.com/quay/quay/issues/1391))
- [f28b35cc](https://github.com/quay/quay/commit/f28b35cc311dae94671cc6bce4b11abc9a68e917): Fix join on caching repo size (PROJQUAY-3889) ([#1378](https://github.com/quay/quay/issues/1378))
- [9d8ff6b1](https://github.com/quay/quay/commit/9d8ff6b1c109fdc285298d32ec2a83069bd90556): address possible integrity exception if computing size concurrently (PROJQUAY-3752) ([#1303](https://github.com/quay/quay/issues/1303))
### Quota API
- [a983884e](https://github.com/quay/quay/commit/a983884e0fe3436acb9cd7f59fdcfcf0e15fe866): Add super user permissions on Organization endpoints (PROJQUAY-3742) ([#1296](https://github.com/quay/quay/issues/1296))
- [2d63be37](https://github.com/quay/quay/commit/2d63be373f69ea03e47864f4681d7fb36b3499d1): Remove trailing backslash (PROJQUAY-3625) ([#1286](https://github.com/quay/quay/issues/1286))
### Quota Management
- [59d586c4](https://github.com/quay/quay/commit/59d586c4c6294ceceb214d2fa1a8fb7e164081c8): Adding default quota check for image push (PROJQUAY-3789) ([#1316](https://github.com/quay/quay/issues/1316))
- [cd288943](https://github.com/quay/quay/commit/cd2889439b6e55e269916d1d5e62fe66d15fb430): Quota settings on Organization view needs to be read only (PROJQUAY-3622) ([#1263](https://github.com/quay/quay/issues/1263))
### Quota UI
- [a0bd9aca](https://github.com/quay/quay/commit/a0bd9aca3efe42c30a45b28f6f2b79d7829250d2): Show quota consumption in whole numbers on super user organizations panel (PROJQUAY-3974) ([#1383](https://github.com/quay/quay/issues/1383))
- [587cceb3](https://github.com/quay/quay/commit/587cceb3386d4b01dbe4b84a74cbf3fde60e82b6): Adding Overall storage consumption for Super users panel page (PROJQUAY-3639) ([#1307](https://github.com/quay/quay/issues/1307))
- [a57594cf](https://github.com/quay/quay/commit/a57594cf017ef043037eb950e8171e086b177720): Fix quota input value (PROJQUAY-3691) ([#1293](https://github.com/quay/quay/issues/1293))
- [03269edc](https://github.com/quay/quay/commit/03269edcbe4f0f499e225905fc3df29a28f0681a): Show message that System wide default cannot be removed from an organization (PROJQUAY-3658) ([#1282](https://github.com/quay/quay/issues/1282))
- [f10690e7](https://github.com/quay/quay/commit/f10690e7d3512a7658bae8779aeae382d9064a3f): Display Error when decimal values entered from UI (PROJQUAY-3627) ([#1272](https://github.com/quay/quay/issues/1272))
- [3176d5ba](https://github.com/quay/quay/commit/3176d5ba41a8c5b0d91e1d1d4b0ea438999d2ea6): Syntax fix to throw error on 0 input (PROJQUAY-3419) ([#1253](https://github.com/quay/quay/issues/1253))
- [923fc72a](https://github.com/quay/quay/commit/923fc72a2821f22a76c07ab90b5e1de707113cae): Showing percent consumed if quota is configured on an organization (PROJQUAY-0000) ([#1249](https://github.com/quay/quay/issues/1249))
### QuotaManagement
- [15fa20a1](https://github.com/quay/quay/commit/15fa20a115b2e82daaa281d2500bfcc902611b1b): Reporting (PROJQUAY-2936) ([#1048](https://github.com/quay/quay/issues/1048))
### README
- [8058bc06](https://github.com/quay/quay/commit/8058bc06427339b342fc64eed55e93e5f957110f): pointing to the correct community list
- [1d1092e4](https://github.com/quay/quay/commit/1d1092e4b4d55c64000951fd9b5a30acd71bc612): link to JBoss JIRA for issue tracking
### README/Docs
- [bef15009](https://github.com/quay/quay/commit/bef1500978ab6c31e2f7f9eec9d134a48e4b12de): s/projectquay/quay in git URIs
### Readme
- [40c68fd8](https://github.com/quay/quay/commit/40c68fd86ba0a4e9873dc5962e431d79a478f534): replace travis badge with github actions ([#359](https://github.com/quay/quay/issues/359))
### Realtime
- [a058235b](https://github.com/quay/quay/commit/a058235b520ea4c1ec7cb9b9c64d6f41a05fc7d9): decode byte to string before using split (PROJQUAY-3180) ([#1107](https://github.com/quay/quay/issues/1107))
### Reconfigure
- [25516930](https://github.com/quay/quay/commit/255169303def620618ec410294d34637852d8821): Add auth to comit to operator endpoint
### Redis
- [ac69360b](https://github.com/quay/quay/commit/ac69360b84422c2f9830df11033ad39df42ded0a): Increase Redis timeout from 3 seconds to 10 seconds
### Refactor(Dockerfile)
- [5ad6e0ff](https://github.com/quay/quay/commit/5ad6e0ffa70cd064b8fe47457f8ec805ab7becb9): use pre-built centos 8 stream ([#936](https://github.com/quay/quay/issues/936))
### Registry
- [23b39720](https://github.com/quay/quay/commit/23b39720d1062fa917926e0f52c14fc886101605): add option to ignore unknown mediatypes (PROJQUAY-5018) ([#1750](https://github.com/quay/quay/issues/1750))
- [c04d0a64](https://github.com/quay/quay/commit/c04d0a644d07e9f3195ef3543df951fe75cfdd95): correctly bump tag expiration when tag changes upstream (PROJQUAY-3976) ([#1479](https://github.com/quay/quay/issues/1479))
- [32322bc1](https://github.com/quay/quay/commit/32322bc1f6bfc919c4366d6063bffb96be491d5a): update blob mount behaviour when from parameter is missing (PROJQUAY-2570) ([#899](https://github.com/quay/quay/issues/899))
- [b0adc966](https://github.com/quay/quay/commit/b0adc9667c906fcf8f7be7b9818768bf4f9311c7): add support for extended repository names (PROJQUAY-1535) ([#814](https://github.com/quay/quay/issues/814))
### Registry_proxy_model
- [514bc6f1](https://github.com/quay/quay/commit/514bc6f1bab18741520f8ddcb77a6421e04752c9): count repository size when caching images (PROJQUAY-3464) ([#1215](https://github.com/quay/quay/issues/1215))
### Release
- [28b36abb](https://github.com/quay/quay/commit/28b36abb27954459f41e01cfe8ecda677aeb0ea3): update downstream Dockerfile (PROJQUAY-1861) ([#851](https://github.com/quay/quay/issues/851))
- [fba629b2](https://github.com/quay/quay/commit/fba629b2dbd2679071ecdfe13d6463a9b96a2fec): fixing Release action (PROJQUAY-1486) ([#723](https://github.com/quay/quay/issues/723))
- [cdd1d1d9](https://github.com/quay/quay/commit/cdd1d1d9d2ac5021277c0625f048c54a0cfe0015): ci/cd release update (PROJQUAY-1486) ([#716](https://github.com/quay/quay/issues/716))
### Repomirror
- [ff66a93e](https://github.com/quay/quay/commit/ff66a93eb7c1b466b2dffd5e62187d7824e6ccad): Add default value for `REPO_MIRROR_ROLLBACK`to config (PROJQUAY-4296) ([#1786](https://github.com/quay/quay/issues/1786))
- [15ea8350](https://github.com/quay/quay/commit/15ea8350db3dd3321801b9b7b8fed8ba252a5b30): Use skopeo list-tags to get repo tags (PROJQUAY-2179) ([#1427](https://github.com/quay/quay/issues/1427))
### Repository
- [a1b7e4b5](https://github.com/quay/quay/commit/a1b7e4b51974edfe86f66788621011eef2667e6a): config to allow public repo create (PROJQUAY-1929) ([#772](https://github.com/quay/quay/issues/772))
### Requirements
- [5c11e7a6](https://github.com/quay/quay/commit/5c11e7a6a64927e46d9c1d7eea68e5c5ab5db2ae): bump cryptography package version ([#939](https://github.com/quay/quay/issues/939))
- [b0d2efb8](https://github.com/quay/quay/commit/b0d2efb8753cd4f4f97f5a2224f01ff7c224e892): use tox-docker upstream
### Requirements-Dev
- [f425f81d](https://github.com/quay/quay/commit/f425f81d1fb64af21284e0741a44c55403f08020): temporarily drop pylint
### Requirements-Osbs
- [12705e49](https://github.com/quay/quay/commit/12705e49c81dd2b932539c1231b47cd80739c689): upgrade cryptography package ([#943](https://github.com/quay/quay/issues/943))
### Requirements-Osbs.Txt
- [f3e016f4](https://github.com/quay/quay/commit/f3e016f4f984286edb3cc0d8a50a5b80dc92e897): remove ipython and related deps ([#1069](https://github.com/quay/quay/issues/1069))
### Requirements.Txt
- [46cd48dd](https://github.com/quay/quay/commit/46cd48dd9febb0b894b2192d10ce649ce5da9bee): bump flask-restful from 0.3.7 to 0.3.9 ([#1375](https://github.com/quay/quay/issues/1375))
- [897e7e39](https://github.com/quay/quay/commit/897e7e3913c0c18436a41b71f582817e8a273187): remove unused dependencies ([#948](https://github.com/quay/quay/issues/948))
### Revert "Chore
- [fe4f7593](https://github.com/quay/quay/commit/fe4f7593eafe890dff68fc2628485b487c4cb645): Use stable Cython ([#2025](https://github.com/quay/quay/issues/2025))" ([#2042](https://github.com/quay/quay/issues/2042))
- [209299fc](https://github.com/quay/quay/commit/209299fc80897f7a7d4b1bf15e047064d40021f9): Bump PyYAML ([#2022](https://github.com/quay/quay/issues/2022))" ([#2041](https://github.com/quay/quay/issues/2041))
- [04358d26](https://github.com/quay/quay/commit/04358d26af974da57b627ab186137a091668fff7): Update Dockerfile to reduce size of image (PROJQUAY-4837) ([#1675](https://github.com/quay/quay/issues/1675))" ([#1678](https://github.com/quay/quay/issues/1678))
- [e4e00f70](https://github.com/quay/quay/commit/e4e00f706a065eeb5fd889a0c2273efa07cd7fb5): Add server side assembly of chunked metadata for RADOSGW driver (PROJQUAY-4592) ([#1557](https://github.com/quay/quay/issues/1557))" ([#1642](https://github.com/quay/quay/issues/1642))
### Revert "Quayio
- [8324586e](https://github.com/quay/quay/commit/8324586e4c577187148a10c93d03ecd2bd34c884): Add export compliance service to Red Hat SSO (PROJQUAY-2056) ([#1239](https://github.com/quay/quay/issues/1239))" ([#1273](https://github.com/quay/quay/issues/1273))
### Revert "Revert "Quayio
- [3140a62e](https://github.com/quay/quay/commit/3140a62e017ae2f19995ca94b1bd3f2bd1c36778): Add export compliance service to Red Hat SSO (PROJQUAY-2056) ([#1239](https://github.com/quay/quay/issues/1239))" ([#1273](https://github.com/quay/quay/issues/1273))" ([#1289](https://github.com/quay/quay/issues/1289))
### Revert "Schema1
- [58b06572](https://github.com/quay/quay/commit/58b065725527ee84fdae3fdf9a7206a860101c68): Permit signed schema1 manifests during conversion (PROJQUAY-PROJQUAY-3285) ([#1146](https://github.com/quay/quay/issues/1146))" ([#1150](https://github.com/quay/quay/issues/1150))
### Revert "Secscan
- [5e4ae649](https://github.com/quay/quay/commit/5e4ae6495a41fd770ea3a986a66d5100e3ab2e75): add metric for scan results (PROJQUAY-4488) ([#1674](https://github.com/quay/quay/issues/1674))" ([#1714](https://github.com/quay/quay/issues/1714))
- [dd1eab52](https://github.com/quay/quay/commit/dd1eab52384c440f1710dc0f95837048e8e4f72c): add a global lock on security worker runs (PROJQUAY-3501) ([#1226](https://github.com/quay/quay/issues/1226))" ([#1232](https://github.com/quay/quay/issues/1232))
### Rhsso
- [0fdf96a2](https://github.com/quay/quay/commit/0fdf96a2d178c3d499ce7f53b5ff8a50e581cd91): Add checks for e-mail blocked in export screen (PROJQUAY-2056) ([#1333](https://github.com/quay/quay/issues/1333))
### S3validation
- [b40c62ce](https://github.com/quay/quay/commit/b40c62ce7dd4715f77a074a5affe3dc0ab3b58ff): Pass token during ec2 role auth (PROJQUAY-2983) ([#153](https://github.com/quay/quay/issues/153))
### Schema1
- [b2dbdcd7](https://github.com/quay/quay/commit/b2dbdcd79813bbe2b1c205c8f6a6a5616851cba9): Generate kid in the correct format (PROJQUAY-3486) ([#1208](https://github.com/quay/quay/issues/1208))
- [b5bd74bf](https://github.com/quay/quay/commit/b5bd74bf051e5de81fede6b386b3fbd178d7b8a8): Permit signed schema1 manifests during conversion (PROJQUAY-PROJQUAY-3285) ([#1146](https://github.com/quay/quay/issues/1146))
### Scripts
- [facb4b1e](https://github.com/quay/quay/commit/facb4b1e5b45eafb25e7f3ae0cbdf90e21a38550): push to ecr backup when building quay.io (PROJQUAY-3273) ([#1578](https://github.com/quay/quay/issues/1578))
### Scripts/Ci
- [43e2d2e5](https://github.com/quay/quay/commit/43e2d2e547915217ae2759e66b53b70183f73bfc): fix incorrect logs command usage
### Sec
- [b389f885](https://github.com/quay/quay/commit/b389f885cfe4e0cd5da18272da50d9b9fc8934fe): implement jwt signing to ClairV4 ([#554](https://github.com/quay/quay/issues/554))
### Secscan
- [c3fc3a82](https://github.com/quay/quay/commit/c3fc3a82ab3280d6df51fcbb955f197a55e39ebe): send notifications for new indexes (PROJQUAY-4659) ([#1813](https://github.com/quay/quay/issues/1813))
- [4aa84a52](https://github.com/quay/quay/commit/4aa84a528c7ad47993c0e8ee123053a48a388644): fix string to int conversion (PROJQUAY-4395) ([#1736](https://github.com/quay/quay/issues/1736))
- [e1985942](https://github.com/quay/quay/commit/e1985942a6eab3b553c35364bcbe365dd4538d72): handle non backfilled layers_compressed_size (PROJQUAY-4395) ([#1734](https://github.com/quay/quay/issues/1734))
- [d84b67c7](https://github.com/quay/quay/commit/d84b67c73ca6d86d0301d90943f79f683c8dad2e): add scan metric (PROJQUAY-4488) ([#1719](https://github.com/quay/quay/issues/1719))
- [80fdb924](https://github.com/quay/quay/commit/80fdb92462ee31a1b56785a7e495c254da16a764): add config to limit manifests with layer size too large to index (PROJQUAY-4957) ([#1733](https://github.com/quay/quay/issues/1733))
- [709487b3](https://github.com/quay/quay/commit/709487b36306fb7721b5cfde0a7648dc83a6bb83): add timeout to indexing requests ([#1727](https://github.com/quay/quay/issues/1727))
- [8f9d6c94](https://github.com/quay/quay/commit/8f9d6c9447b3e8dc8d0b94dad4417b5bbeb41ff4): add metric for scan results (PROJQUAY-4488) ([#1674](https://github.com/quay/quay/issues/1674))
- [84786b9c](https://github.com/quay/quay/commit/84786b9c6fcf851c2beeb04e1c61683ec22dd46f): Correct links (PROJQUAY-2164) ([#1552](https://github.com/quay/quay/issues/1552))
- [98801bfd](https://github.com/quay/quay/commit/98801bfd3e8cb0b81f83cbbcac0346302eef7b8c): Generate key to reduce vulnerabilities (PROJQUAY-4562) ([#1547](https://github.com/quay/quay/issues/1547))
- [5291daf8](https://github.com/quay/quay/commit/5291daf8fe22218995eb37e4ef6f8b3a481bdd2b): Don't delete manifest security status on error (PROJQUAY-4060) ([#1434](https://github.com/quay/quay/issues/1434))
- [5471d3cb](https://github.com/quay/quay/commit/5471d3cbcb4d4f923d1b1007677f20118eec8f6f): deprecate support for Clair V2 (PROJQUAY-2837) ([#951](https://github.com/quay/quay/issues/951))
- [776dbd90](https://github.com/quay/quay/commit/776dbd90d5d898776dff1a9a87d933bdfbc9a7b2): update https proxy scheme ([#1340](https://github.com/quay/quay/issues/1340))
- [3acc55b9](https://github.com/quay/quay/commit/3acc55b96c0c64e9fcdbd6af359579a0714406b1): split the recent manifest chunk of work into multiple batch (PROJQUAY-3501) ([#1300](https://github.com/quay/quay/issues/1300))
- [f3c3916b](https://github.com/quay/quay/commit/f3c3916bc732642bca747c252d4764814441dd9a): add option to skip recent manifest batch lock (PROJQUAY-3501) ([#1299](https://github.com/quay/quay/issues/1299))
- [9ac30007](https://github.com/quay/quay/commit/9ac30007f9ded33e1f8123ae887b730e97de7709): cleanup secscan interface (PROJQUAY-3501) ([#1284](https://github.com/quay/quay/issues/1284))
- [72c8d7a3](https://github.com/quay/quay/commit/72c8d7a3c51dbb409326826ff444d72cf6cca984): fix config reference (PROJQUAY-3501) ([#1283](https://github.com/quay/quay/issues/1283))
- [ed77147b](https://github.com/quay/quay/commit/ed77147b2166160b9d0d09cda23e90fea2d20e44): split indexing of recent manifest into separate background operation (PROJQUAY-3501) ([#1281](https://github.com/quay/quay/issues/1281))
- [035f5820](https://github.com/quay/quay/commit/035f58207532e4254546ea1691a0a74592047682): fix check for end of table (PROJQUAY-3501) ([#1270](https://github.com/quay/quay/issues/1270))
- [a9e1b71a](https://github.com/quay/quay/commit/a9e1b71a2c34dd88a2e15f2a881d9b4afcfe83e3): fix missing import (PROJQUAY-3501) ([#1261](https://github.com/quay/quay/issues/1261))
- [922892d1](https://github.com/quay/quay/commit/922892d1af262d2eb18f9a9dba05cd6efc2d91e2): configure global lock (PROJQUAY-3501) ([#1255](https://github.com/quay/quay/issues/1255))
- [7d0f318b](https://github.com/quay/quay/commit/7d0f318baa62289137911c5f350a98c844866ce9): update the secscan model interface (PROJQUAY-3501) ([#1254](https://github.com/quay/quay/issues/1254))
- [d719dfad](https://github.com/quay/quay/commit/d719dfadc5f89eca4563337ef085ba7effbac23c): optimize deduplicating manifests for indexing in securityworker (PROJQUAY-3501) ([#1247](https://github.com/quay/quay/issues/1247))
- [53aaa549](https://github.com/quay/quay/commit/53aaa5493bf2c0bbc627fd70cb0fd273f75be076): add indexer service request duration metric (PROJQUAY-3501) ([#1243](https://github.com/quay/quay/issues/1243))
- [a52b0026](https://github.com/quay/quay/commit/a52b00263a5d71c85fa0201fe2b5b15ed8f8ee53): fix database manifest allocator for securityworker (PROJQUAY-3501) ([#1235](https://github.com/quay/quay/issues/1235))
- [9d89b6fa](https://github.com/quay/quay/commit/9d89b6fa47dec4ab0c182d88f56772303adc09a6): add a global lock on security worker runs (PROJQUAY-3501) ([#1226](https://github.com/quay/quay/issues/1226))
- [4295a8f6](https://github.com/quay/quay/commit/4295a8f6604144049b59233371bf508edf3cffc0): scan recent manifests in addition to regular backfill (PROJQUAY-3287) ([#1169](https://github.com/quay/quay/issues/1169))
- [6a8567f8](https://github.com/quay/quay/commit/6a8567f830db1f4835a6e585a8ce3b74f78f94eb): log manifest ID when indexing (PROJQUAY-3287) ([#1166](https://github.com/quay/quay/issues/1166))
- [2b2e795b](https://github.com/quay/quay/commit/2b2e795b9c65e055c221304c43ef5cdbe91c563e): Log start and end index of block in clair (PROJQUAY-3287) ([#1165](https://github.com/quay/quay/issues/1165))
- [7162be37](https://github.com/quay/quay/commit/7162be3791db1ef122a579e5546857dbb55314f3): make batch_size configurable (PROJQUAY-3287) ([#1156](https://github.com/quay/quay/issues/1156))
- [369ee78a](https://github.com/quay/quay/commit/369ee78a2cec2024c0ee31f2b92190d3d69c9286): clairv2 - fix datatype bug (PROJQUAY-3279) ([#1138](https://github.com/quay/quay/issues/1138))
- [b32ca314](https://github.com/quay/quay/commit/b32ca3142a7255d91d70b267fcaee078ed54bc56): ClairV2 datatype compatibility (PROJQUAY-3279) ([#1133](https://github.com/quay/quay/issues/1133))
- [26eb7ff9](https://github.com/quay/quay/commit/26eb7ff9827fda97f775104a3b0d6a04c63ea860): Don't save secscan result if returned state is unknown (PROJQUAY-2939) ([#1047](https://github.com/quay/quay/issues/1047))
- [9f16b324](https://github.com/quay/quay/commit/9f16b3247e1fdd2a97f773657f722067388a8761): fix secscan api ApiRequestFailure test (PROJQUAY-2563) ([#896](https://github.com/quay/quay/issues/896))
- [694fa2ac](https://github.com/quay/quay/commit/694fa2acafbf50d09b1cccb54dcdd3c4aec3c113): continue iterating after failure (PROJQUAY-2563) ([#892](https://github.com/quay/quay/issues/892))
- [79e97785](https://github.com/quay/quay/commit/79e9778576e715da04a5eafc8dbde2e78955a095): handle proxy model fallback to noop v2 (PROJQUAY-2289) ([#847](https://github.com/quay/quay/issues/847))
- [65ec47ab](https://github.com/quay/quay/commit/65ec47ab4b67fcd84fb9a7aa0b4f9f31c5b4d902): handle remote layer url when sending request to Clair (PROJQUAY-2269) ([#841](https://github.com/quay/quay/issues/841))
- [311241af](https://github.com/quay/quay/commit/311241af09be60d0f5a1e844d5722d96aaf61395): allow basic auth on the secscan api endpoint when anonymous api resource is set. ([#608](https://github.com/quay/quay/issues/608))
### Secscan
- [fa0e8618](https://github.com/quay/quay/commit/fa0e8618494138dc78c8496c0d9d6d83b66335ca): clair v4 enrichment (PROJQUAY-2102) ([#840](https://github.com/quay/quay/issues/840))
### Secscan_model
- [37578247](https://github.com/quay/quay/commit/37578247088bc86e80f33f106d8aac5177b488f0): attempt urldecoding `fixed_in_version` (PROJQUAY-5886) ([#2063](https://github.com/quay/quay/issues/2063))
### Security
- [95a59325](https://github.com/quay/quay/commit/95a5932528cde8937a21cf88fe45a5664c44489f): Change error messages in UI during LDAP login (PROJQUAY-4845) ([#1767](https://github.com/quay/quay/issues/1767))
### Securityscanner
- [1a4e817b](https://github.com/quay/quay/commit/1a4e817bf3f8cbbc2baeb8aa69cf84be7dabcba3): validate introspection endpoint (PROJQUAY-1610)
### Sescan
- [4db59990](https://github.com/quay/quay/commit/4db59990372e59c1de436d3fa7f3715e90887e0c): prioritize scanning new pushes (PROJQUAY-3287) ([#1147](https://github.com/quay/quay/issues/1147))
### Setup
- [92c96876](https://github.com/quay/quay/commit/92c9687656cdf9fcf878ff0553665c89918ef61b): Add ALLOWED_OCI_ARFICAT_TYPES to generated config (PROJQUAY-1032) ([#110](https://github.com/quay/quay/issues/110))
- [fd190ad9](https://github.com/quay/quay/commit/fd190ad98468bbeb911bc2327faec14e84764265): Export Quay modules (PROJQUAY-3181) ([#1108](https://github.com/quay/quay/issues/1108))
### Smtp
- [764673d2](https://github.com/quay/quay/commit/764673d2d2152aab600480a07b672bb3d7041e9f): Use TLS certs when connecting to smpt (PROJQUAY-1605) ([#175](https://github.com/quay/quay/issues/175))
### Ssl
- [89755418](https://github.com/quay/quay/commit/89755418fd08b06682a45bc1d3530e1552fbee94): re-enable .key file loading (PROJQUAY-2511) ([#123](https://github.com/quay/quay/issues/123))
### Sso
- [ca70a501](https://github.com/quay/quay/commit/ca70a501c6095ef2953fb37c032cdfec624dddd8): Handle edge case for stage sso only users (PROJQUAY-2056) ([#1326](https://github.com/quay/quay/issues/1326))
- [42f09298](https://github.com/quay/quay/commit/42f09298c453133da73bb4b9b363fb2ffed4b928): Fix debug statement (PROJQUAY-2056) ([#1325](https://github.com/quay/quay/issues/1325))
- [f6e754b5](https://github.com/quay/quay/commit/f6e754b561a0ebf356d34d6d56ca3f9f539eb4f1): Use trusted cert from extra_ca_certs directory (PROJQUAY-2056) ([#1324](https://github.com/quay/quay/issues/1324))
- [0826ac0e](https://github.com/quay/quay/commit/0826ac0e4e6da68dab99a9746e09c5181b2e516b): Use requests client in screening call (PROJQUAY-2056) ([#1321](https://github.com/quay/quay/issues/1321))
- [4e739d30](https://github.com/quay/quay/commit/4e739d30bf6be74b5094012ab5aae91865a59ef7): Update mount path for export compliance certificate (PROJQUAY-2056) ([#1320](https://github.com/quay/quay/issues/1320))
- [2c3e26a3](https://github.com/quay/quay/commit/2c3e26a322501aef73d887fc2346ef7e1610fdff): Add test for RHSSO OAuth service (PROJQUAY-2056) ([#1317](https://github.com/quay/quay/issues/1317))
### Static
- [a13baef9](https://github.com/quay/quay/commit/a13baef9cc15c68f41fd24e0f21a05979f5b4fbd): vendor webfonts dir ([#1016](https://github.com/quay/quay/issues/1016))
- [ab499e8f](https://github.com/quay/quay/commit/ab499e8f2cc72b90d07890bd8b1a5513594ef280): vendor external libraries ([#1014](https://github.com/quay/quay/issues/1014))
### Storage
- [63888379](https://github.com/quay/quay/commit/63888379812908c52c22d951b794af04545835b2): add option to validate all configured storages (PROJQUAY-5074) ([#1752](https://github.com/quay/quay/issues/1752))
- [bbdefcb8](https://github.com/quay/quay/commit/bbdefcb8eace5dfaf9c5c9f891d47268c4740700): Add CloudFlare and MultiCDN config validation (PROJQUAY-5048) ([#199](https://github.com/quay/quay/issues/199))
- [0ae31c6e](https://github.com/quay/quay/commit/0ae31c6ebcbc1441a18e33eb2e3c8be1c1e90d81): Add MultiCDN storage provider (PROJQUAY-5048) ([#1747](https://github.com/quay/quay/issues/1747))
- [f4d9dda2](https://github.com/quay/quay/commit/f4d9dda27d59df582b73d0a57122cae335123799): Add **kwargs to get_direct_download_url for CloudFlare storage (PROJQUAY-3512) ([#1594](https://github.com/quay/quay/issues/1594))
- [40735569](https://github.com/quay/quay/commit/407355691ba593ca9a26ffd9be48cd4826c89669): Add Cloudflare as a CDN provider for an S3 backed storage (PROJQUAY-3699) ([#1294](https://github.com/quay/quay/issues/1294))
- [47564690](https://github.com/quay/quay/commit/47564690071c02a6f7d5cf7b5ac1c9a102ab7523): handle KeyError we sometimes get from aws ([#1543](https://github.com/quay/quay/issues/1543))
- [a101553c](https://github.com/quay/quay/commit/a101553cb1bae22cdf4b16e37a3a3a2bc8645e48): return S3 url only for ip ranges in the same region (PROJQUAY-4498) ([#1539](https://github.com/quay/quay/issues/1539))
- [e6be9fc4](https://github.com/quay/quay/commit/e6be9fc43a04c2770b82927b939f9347f270b7cb): Add username field to requests on CloudFront (PROJQUAY-3511) ([#1486](https://github.com/quay/quay/issues/1486))
- [56b16b70](https://github.com/quay/quay/commit/56b16b70cca1ff0f5f51dd2fb47852027d66eef6): optimize large azure chunked upload (PROJQUAY-3753) ([#1387](https://github.com/quay/quay/issues/1387))
- [c9c91339](https://github.com/quay/quay/commit/c9c9133914da3e931bab1e21255444a8fbf3e762): allow arbitrary endpoint url for azure storage ([#1071](https://github.com/quay/quay/issues/1071))
- [13a9f8f4](https://github.com/quay/quay/commit/13a9f8f44e59d512c4f01e5cc94a03bd8fca3d10): Add cn-northwest-1 to s3_region northwest (PROJQUAY-3082) ([#1137](https://github.com/quay/quay/issues/1137))
- [ca17eb43](https://github.com/quay/quay/commit/ca17eb43121e4d8ce85bc470e8f90c8feb2551e5): handle cn-north-1 region (PROJQUAY-3082) ([#1129](https://github.com/quay/quay/issues/1129))
- [f6f7b05a](https://github.com/quay/quay/commit/f6f7b05a060edd216354e632854c6ee0f545a768): allow configuration of storage region for cloud storage (PROJQUAY-3082) ([#1081](https://github.com/quay/quay/issues/1081))
- [c5a1a7c0](https://github.com/quay/quay/commit/c5a1a7c0ccb56c4b432c63d947a1a37a7bde3205): Do not require a storage_path in Distributed Storage Configuration ([#133](https://github.com/quay/quay/issues/133))
- [fd274682](https://github.com/quay/quay/commit/fd2746827a48100d5aba7316b20724d25104817e): fix us-east-2 S3 direct pull ([#714](https://github.com/quay/quay/issues/714))
- [e0d39fe9](https://github.com/quay/quay/commit/e0d39fe9f24c01c4a893066fb9c71477ea9d90e5): abort unfinished mpu when no bytes were written ([#705](https://github.com/quay/quay/issues/705))
### Storagereplication
- [c0efc752](https://github.com/quay/quay/commit/c0efc75207a50cf6d168fe16bc887ff43c834d8b): add retry logic without exhausting queue retries (PROJQUAY-4793) ([#1832](https://github.com/quay/quay/issues/1832))
- [2e5f2572](https://github.com/quay/quay/commit/2e5f25726aae04c6527a2c8a5399d3e6ab03cf7a): sleep on unexpected exception for retry (PROJQUAY-4792) ([#1792](https://github.com/quay/quay/issues/1792))
### Superuser
- [9adf2d8c](https://github.com/quay/quay/commit/9adf2d8cf05303668362d176ac655e9969408116): paginate user's list (PROJQUAY-4297) ([#1881](https://github.com/quay/quay/issues/1881))
- [c505a6ba](https://github.com/quay/quay/commit/c505a6bae8c93c4bead3acffc189c4d5e5bfef96): paginating superuser organization list (PROJQUAY-4297) ([#1876](https://github.com/quay/quay/issues/1876))
- [dad7dfaf](https://github.com/quay/quay/commit/dad7dfaf44da08d4c39c99443c488f026bfa82f3): Fix display of build logs (PROJQUAY-3404) ([#1185](https://github.com/quay/quay/issues/1185))
### Superusers
- [45d00a6b](https://github.com/quay/quay/commit/45d00a6b8ff9989e893c656a3e71ad7cf09d144f): gives superusers access to team invite api (PROJQUAY-4765) ([#1694](https://github.com/quay/quay/issues/1694))
- [64ec1560](https://github.com/quay/quay/commit/64ec15605c6dd8d3e1d66442c97a4511c6d22d04): grant superusers additinonal org permissions (PROJQUAY-4687) ([#1613](https://github.com/quay/quay/issues/1613))
### Tags
- [79faf5f3](https://github.com/quay/quay/commit/79faf5f3679b3ac416c13b70f9fd101d496a6eef): apply tag expiry to created tags pointing to existing manifest ([#690](https://github.com/quay/quay/issues/690))
### Task
- [eb308136](https://github.com/quay/quay/commit/eb308136836ccbe64bbaf143ef67330e72a5010e): remove obsolete logrotate.conf file (PROJQUAY-4364) ([#1500](https://github.com/quay/quay/issues/1500))
### Teams
- [639833cc](https://github.com/quay/quay/commit/639833cc15304ec184f51843e18e2337dc29059f): admin team deletion (PROJQUAY-2080) ([#1077](https://github.com/quay/quay/issues/1077))
### Templates
- [1c157e2a](https://github.com/quay/quay/commit/1c157e2a5b3ad4d091bc9480761b850d8856a15a): escape templated script value (PROJQUAY-970) ([#828](https://github.com/quay/quay/issues/828))
### Tests
- [300309db](https://github.com/quay/quay/commit/300309dbc4c38d70d92702ce859583d5fe28c443): fix tox
### Tls
- [ca5a4280](https://github.com/quay/quay/commit/ca5a4280493c5ee9d99d97f3095fa399b2f98fc1): Set external tls termination flag to false when internal (PROJQUAY-2428) ([#124](https://github.com/quay/quay/issues/124))
### Tlscomponent
- [ddc1b3de](https://github.com/quay/quay/commit/ddc1b3de8124fc4f922663a949d8dd2c2e10fdc5): changing option message for custom tls (PROJQUAY-2428) ([#117](https://github.com/quay/quay/issues/117))
### Tox
- [5f43b3f8](https://github.com/quay/quay/commit/5f43b3f81e1e6047ebab21357ed2facf6980fa5b): allow /bin/sh (PROJQUAY-5092) ([#1757](https://github.com/quay/quay/issues/1757))
- [8bb05771](https://github.com/quay/quay/commit/8bb05771717ab7e5f8786b6c1c8fdff4660bbb17): out python version for sanity
- [b2eb7530](https://github.com/quay/quay/commit/b2eb7530730cab9e53deb6e4e28af6990551a37f): remove legacy test suite
- [73595761](https://github.com/quay/quay/commit/73595761e3b81a31a4f5b54f2e4ec697ab9aa30f): use tox-docker fork for manual ports
- [4f0209b3](https://github.com/quay/quay/commit/4f0209b318a65c8d0c77931305d449c0b507d9d9): use /bin/sh instead of python to export env
- [a496ba5e](https://github.com/quay/quay/commit/a496ba5e132502ed3d9e07e0aa8cef68cd2cb50a): container healthchecks
- [987f20a3](https://github.com/quay/quay/commit/987f20a31c0de65054b4896f819313551a5efe28): init tox-docker
### Travis
- [27bc7bad](https://github.com/quay/quay/commit/27bc7bad254e65b5ec20e75db226c0efa63716c2): s/state/stage
### Travis CI: Sudo
- [dede6d30](https://github.com/quay/quay/commit/dede6d30de85f70408cdda670193560a8b77fe42): is fully deprecated in Travis
### Trigger_analyzer
- [861c247f](https://github.com/quay/quay/commit/861c247faf75e60a8ffde0ee58e0148abbb5efb2): fix confusing print (PROJQUAY-1995) ([#1073](https://github.com/quay/quay/issues/1073))
### UI
- [5198db57](https://github.com/quay/quay/commit/5198db57445487a32adcaa066d4acb2ae422de9b): Robot Accounts page perms fix (PROJQUAY-5487) ([#2088](https://github.com/quay/quay/issues/2088))
- [8c21856b](https://github.com/quay/quay/commit/8c21856b716c9a4279fdf32d3d0ba5290c9479a2): Delete normal user org by super user (PROJQUAY-5639) ([#2008](https://github.com/quay/quay/issues/2008))
- [98a0f8bb](https://github.com/quay/quay/commit/98a0f8bb4d7a79be95310544c37647baaf0b0ac2): Fixing failing tests ([#1890](https://github.com/quay/quay/issues/1890))
- [c014b6af](https://github.com/quay/quay/commit/c014b6af03d98a29538ef2f0dd534f2e8a3d4c23): Adding functionality to update organization settings (PROJQUAY-5402) ([#1864](https://github.com/quay/quay/issues/1864))
- [7be6c3d2](https://github.com/quay/quay/commit/7be6c3d22780f4b6811bb3853a271753e2a7021c): Fix visibility of organization and user settings on new UI (PROJQUAY-5500) ([#1882](https://github.com/quay/quay/issues/1882))
- [e6d834f2](https://github.com/quay/quay/commit/e6d834f23d562f7e00f2e63c2d91590870a7a410): Fixing repository name for nested repos (PROJQUAY-5446) ([#1873](https://github.com/quay/quay/issues/1873))
- [37723b96](https://github.com/quay/quay/commit/37723b964cca099b334962df90b4115bc1ae026b): Removing Cancel button from Robot account credentials modal (PROJQUAY-5426) ([#1867](https://github.com/quay/quay/issues/1867))
- [c6f35b3d](https://github.com/quay/quay/commit/c6f35b3d25cf99f2517cf478e4cc9e5ee55119d9): Removing isHidden from Tab as incompatible with console dot (PROJQUAY-4553) ([#1863](https://github.com/quay/quay/issues/1863))
- [dcd192d5](https://github.com/quay/quay/commit/dcd192d5249e77ccb99c09c86a3a0475172e2bc1): Using organizationName variable and using isHidden to hide tabs (PROJQUAY-4553) ([#1862](https://github.com/quay/quay/issues/1862))
- [d20fd5e7](https://github.com/quay/quay/commit/d20fd5e7468912d6b741aa4594549e1f335e75b6): Robot token fetch & regenerate fix for user namespace (PROJQUAY-5419) ([#1860](https://github.com/quay/quay/issues/1860))
- [22d28f9f](https://github.com/quay/quay/commit/22d28f9fcdea157d503c36bcac307535f92a3973): Filtering security report vulnerabilities (PROJQUAY-5401) ([#1861](https://github.com/quay/quay/issues/1861))
- [1634f817](https://github.com/quay/quay/commit/1634f8176b6fe3e7115eaef280aad11817d530e8): Fixing Teams search in Create Robot Wizard (PROJQUAY-5403) ([#1859](https://github.com/quay/quay/issues/1859))
- [b95a4f6a](https://github.com/quay/quay/commit/b95a4f6aaae9fc9c7ad9ac68dfe4779de13a01f2): Replacing FilterInput with SearchInput in repo search for create robot account wizard (PROJQUAY-5403) ([#1851](https://github.com/quay/quay/issues/1851))
- [155165d6](https://github.com/quay/quay/commit/155165d6dae4332fd653611dcef22985ffb5e3ef): Replacing FilterInput with SearchInput in Robot accounts page (PROJQUAY-5404) ([#1849](https://github.com/quay/quay/issues/1849))
- [2616bf9b](https://github.com/quay/quay/commit/2616bf9b9a2ca4075c471c72372f97c4b27c548d): Replacing useRecoil with useState for robot account search (PROJQUAY-5404) ([#1848](https://github.com/quay/quay/issues/1848))
- [d9b9f60c](https://github.com/quay/quay/commit/d9b9f60c59e741bca7316bf3228c88375d5d553f): Check if org is user for robot creation (PROJQUAY-5398) ([#1847](https://github.com/quay/quay/issues/1847))
- [71cfdca0](https://github.com/quay/quay/commit/71cfdca0879cacbf9affe036b1724776ddf0b406): Fixing repoDetails not defined error ([#1837](https://github.com/quay/quay/issues/1837))
- [60181dae](https://github.com/quay/quay/commit/60181dae0313ca4023bfe7e4076acf551a3b1ca4): Fix redirection to user/org page (PROJQUAY-4667) ([#1623](https://github.com/quay/quay/issues/1623))
- [ba2aa54d](https://github.com/quay/quay/commit/ba2aa54d3fc081c052d65c899b49f67dd6ca3ada): Superuser user panel settings icon permissions fix (PROJQUAY-3905) ([#1364](https://github.com/quay/quay/issues/1364))
- [c93661e9](https://github.com/quay/quay/commit/c93661e9d51a645b43760db83b20f8b9c8041d3c): Show settings icon for super user under Superuser Users Panel (PROJQUAY-3905) ([#1358](https://github.com/quay/quay/issues/1358))
- [3d6545b9](https://github.com/quay/quay/commit/3d6545b9da1c32591ab0945b1d66282ce058a051): Quota UI enhancements (PROJQUAY-0000) ([#1242](https://github.com/quay/quay/issues/1242))
### Ui
- [e5cd8114](https://github.com/quay/quay/commit/e5cd81143f2187b07fbce70dc8bb3ab1de59ac24): fixing cypress flake (PROJQUAY-8352) ([#3521](https://github.com/quay/quay/issues/3521))
- [74d6d827](https://github.com/quay/quay/commit/74d6d82748df7fc9b5dcb5f1e712fd3be1b7b38f): updating quota size format (PROJQUAY-5471) ([#1886](https://github.com/quay/quay/issues/1886))
- [a681a0b7](https://github.com/quay/quay/commit/a681a0b71da9c1147caa146af8b94d48e63fb909): Fix search in bulk delete of robot accounts (PROJQUAY-5355) ([#1868](https://github.com/quay/quay/issues/1868))
- [0029b8b4](https://github.com/quay/quay/commit/0029b8b4ae2c44c01ca58b6df2022262dba1cedf): update survey link to new survey (PROJQUAY-5432) ([#1865](https://github.com/quay/quay/issues/1865))
- [93de6539](https://github.com/quay/quay/commit/93de653973c8463eabe8dbeb8ca463a6801dfbbd): Hide organization settings when user is not admin (PROJQUAY-4053) ([#1829](https://github.com/quay/quay/issues/1829))
- [be1424ca](https://github.com/quay/quay/commit/be1424ca3a1150ec10b5940ffc369ac9abdf10db): Adding option to permanently delete tags past time machine window (PROJQUAY-5303) ([#1853](https://github.com/quay/quay/issues/1853))
- [64e4e327](https://github.com/quay/quay/commit/64e4e32704181b398129f318b555b1dd0840e6b9): fix last modified date on repo list (PROJQUAY-5408) ([#1854](https://github.com/quay/quay/issues/1854))
- [f22da92e](https://github.com/quay/quay/commit/f22da92e6b773125f0dbfd5b08bdb9f13886ede9): use route location instead of window.location (PROJQUAY-5392) ([#1844](https://github.com/quay/quay/issues/1844))
- [19259c1c](https://github.com/quay/quay/commit/19259c1cb0cf9ca0ceb0397b842f4d37089b3266): Refresh auth token for plugin flow on 401 (PROJQUAY-5390) ([#1843](https://github.com/quay/quay/issues/1843))
- [717db76c](https://github.com/quay/quay/commit/717db76ca20907f74e4eac04c8692c55960f6102): Use the correct endpoint for plugin (PROJQUAY-3203) ([#1842](https://github.com/quay/quay/issues/1842))
- [2db3b186](https://github.com/quay/quay/commit/2db3b186f9e2bb60251d15fd5b3b7cba90851045): add support for exposing quay UI as a dynamic plugin (PROJQUAY-3203) ([#1799](https://github.com/quay/quay/issues/1799))
- [0e3221e4](https://github.com/quay/quay/commit/0e3221e4f3c7d9d3c5d86d25ac072b89f52faa3d): Merge quay-ui into quay (PROJQUAY-5315) ([#1827](https://github.com/quay/quay/issues/1827))
- [85218f11](https://github.com/quay/quay/commit/85218f1112677a0af59810859950353465e72456): Hot fix billing information (PROJQUAY-0000) ([#1679](https://github.com/quay/quay/issues/1679))
- [b8cf8932](https://github.com/quay/quay/commit/b8cf8932cf34c738160a290a9b337018d9daf26b): Repository settings feature flag (PROJQUAY-4565) ([#1677](https://github.com/quay/quay/issues/1677))
- [1a2bb4a4](https://github.com/quay/quay/commit/1a2bb4a4e918c032bb16a61c4045fcabef886494): Remove add_analytics script from Dockerfile (PROJQUAY-4582) ([#1669](https://github.com/quay/quay/issues/1669))
- [74d8a515](https://github.com/quay/quay/commit/74d8a515f882db7b5a5ac59c8f4e0399a60f4e34): Remove FEATURE_UI_V2 from analytics scripts (PROJQUAY-4582) ([#1658](https://github.com/quay/quay/issues/1658))
- [c71fd10b](https://github.com/quay/quay/commit/c71fd10bc2e3a96a41d518fa2e9b8d1b38e8d882): Add script for adobe analytics for quay.io in angular UI (PROJQUAY-4582) ([#1654](https://github.com/quay/quay/issues/1654))
- [8211b774](https://github.com/quay/quay/commit/8211b774bc8cebd36d923b3710ad7b70711a889f): Show UI toggle on quay.io only to redhat users (PROJQUAY-4804) ([#1653](https://github.com/quay/quay/issues/1653))
- [bc5bc22b](https://github.com/quay/quay/commit/bc5bc22b1d8bbdeaa841d956661dd4d58073911d): Add script for adobe analytics for quay.io (PROJQUAY-4582) ([#1648](https://github.com/quay/quay/issues/1648))
- [96372019](https://github.com/quay/quay/commit/963720190386460b073782c090319894b3b3936b): Fix font size in superuser page (PROJQUAY-4407) ([#1553](https://github.com/quay/quay/issues/1553))
- [5f1fdbc5](https://github.com/quay/quay/commit/5f1fdbc59ff491dcef1531d69fb1393df26f8ffc): Support on Old UI to switch to New UI (PROJQUAY-4124) ([#1504](https://github.com/quay/quay/issues/1504))
- [b1d13d16](https://github.com/quay/quay/commit/b1d13d1622f5df33c561a81ad317b647e6b43524): Remove trial from larger plans for quay.io (PROJQUAY-4197) ([#1459](https://github.com/quay/quay/issues/1459))
- [7cbf0ffd](https://github.com/quay/quay/commit/7cbf0ffd7d3bf3c6de1943af2f638f4eb90b038c): Remove trial from larger plans for quay.io (PROJQUAY-4197) ([#1455](https://github.com/quay/quay/issues/1455))
- [1a016efc](https://github.com/quay/quay/commit/1a016efc80220c7c62b723ce62a4044d7d8b9a24): Add CSRF and token endpoint and public config endpoint (PROJQUAY-3865) ([#1323](https://github.com/quay/quay/issues/1323))
- [d9dbbd88](https://github.com/quay/quay/commit/d9dbbd88dbb9a1da95ef46195bcfb5458db6a7b8): basic support for cosign in the UI (PROJQUAY-3965) ([#1380](https://github.com/quay/quay/issues/1380))
- [e67ea047](https://github.com/quay/quay/commit/e67ea047c41e0feeb191d17a868f39df772da31a): Copy build logs error fix (PROJQUAY-3405) ([#1201](https://github.com/quay/quay/issues/1201))
- [815ef446](https://github.com/quay/quay/commit/815ef44651d0e4a4e6ad4e23f2e77fb58efbaf73): remove deprecated docker-image-id references from ui (PROJQUAY-3418) ([#1197](https://github.com/quay/quay/issues/1197))
- [76146760](https://github.com/quay/quay/commit/76146760493870bfc8b9860ad901e91ddcf3ad78): Show extra_ca_cert_ prefix (PROJQUAY-3318) ([#158](https://github.com/quay/quay/issues/158))
- [033c1aaf](https://github.com/quay/quay/commit/033c1aafa1d1364a41a0861f16fa1769315672d6): display manifest list manifest sizes (PROJQUAY-3196) ([#1115](https://github.com/quay/quay/issues/1115))
- [e91ec644](https://github.com/quay/quay/commit/e91ec644fa9581f55a583c7d03a68a9f957c9f03): Depricate getImageCommand in security UI (PROJQUAY-3284) ([#1144](https://github.com/quay/quay/issues/1144))
- [374e957b](https://github.com/quay/quay/commit/374e957bd93d5b6bbb6ddd2080aaa4d67fcdfa74): fix csrf issue when login in with SSO on mobile (PROJQUAY-2340) ([#906](https://github.com/quay/quay/issues/906))
- [bf81bd9b](https://github.com/quay/quay/commit/bf81bd9bae44f6ff870d207026f44010e1b2d229): change angular routing order for repo paths (PROJQUAY-2325) ([#872](https://github.com/quay/quay/issues/872))
- [a180c52a](https://github.com/quay/quay/commit/a180c52aaab7f7cd7ecc72c5a41b85c75970300e): force uses to sign-in page to fix SSO CSRF cookie issue (PROJQUAY-2340) ([#865](https://github.com/quay/quay/issues/865))
- [97fc1b5c](https://github.com/quay/quay/commit/97fc1b5cc774dbc6d085490548dc4695b440d55e): Require user to enter repository when deleting (PROJQUAY-763) ([#432](https://github.com/quay/quay/issues/432))
- [de12ed74](https://github.com/quay/quay/commit/de12ed7482859e3d6d4ce89d5ece2e701996d6ee): Add repo state column when mirroring enabled (PROJQUAY-591) ([#419](https://github.com/quay/quay/issues/419))
### User
- [1e136d6d](https://github.com/quay/quay/commit/1e136d6dd0fec70cb6e4cbd442ef1768aab1592d): Added function to fetch users public repositories count (PROJQUAY-0000) ([#1540](https://github.com/quay/quay/issues/1540))
### Users
- [dba302b5](https://github.com/quay/quay/commit/dba302b5f162b7800f676cf4789cc4e40898f240): default to true if LDAP_RESTRICTED_USER_FILTER is not set (PROJQUAY-4776) ([#1645](https://github.com/quay/quay/issues/1645))
- [b128936b](https://github.com/quay/quay/commit/b128936b504dbe0f2083d1784d884cb877db9c97): fix behavior when using ldap and restricted user whitelist is set (PROJQUAY-4767) ([#1640](https://github.com/quay/quay/issues/1640))
- [7cd55ea0](https://github.com/quay/quay/commit/7cd55ea0cd4a3fc7a995a26be51e8709bc1785be): fix create repo on push on orgs for restricted users (PROJQUAY-4732) ([#1634](https://github.com/quay/quay/issues/1634))
- [0caa4203](https://github.com/quay/quay/commit/0caa4203eccc21895a5e84322e68db18d5ad959f): prevent CREATE_NAMESPACE_ON_PUSH is restricted (PROJQUAY-4702) ([#1621](https://github.com/quay/quay/issues/1621))
- [8fc03857](https://github.com/quay/quay/commit/8fc03857cbd3cde85217138389fc08dbecfc2b53): when set, grant superusers repository permissions. ([#1620](https://github.com/quay/quay/issues/1620))
- [ef8ad2c3](https://github.com/quay/quay/commit/ef8ad2c3e1efec3719ed6ceb249acf9b7b617fd9): prevent creating repo on push for restricted users (PROJQUAY-4706) ([#1614](https://github.com/quay/quay/issues/1614))
- [c84067a4](https://github.com/quay/quay/commit/c84067a4d6a1a4442c13f841aab9cd448857db37): add restricted users' filter (PROJQUAY-1245) ([#1551](https://github.com/quay/quay/issues/1551))
- [14e87bd4](https://github.com/quay/quay/commit/14e87bd41e393032576fd23daf4801ea5f7def22): fix missing references in ldap for superusers ([#1542](https://github.com/quay/quay/issues/1542))
- [070f464b](https://github.com/quay/quay/commit/070f464b149695b79d837fd781bd72aadde5753e): superuser group in federated identity provider (PROJQUAY-3924) ([#1464](https://github.com/quay/quay/issues/1464))
### Util
- [42d1cdb4](https://github.com/quay/quay/commit/42d1cdb4a16e961a23b4af9126c96798ecabb7fa): update aws-ip-ranges.json ([#1143](https://github.com/quay/quay/issues/1143))
- [cfd4e8c4](https://github.com/quay/quay/commit/cfd4e8c46b7f174c3bc028a843293e58a5d37eab): fix matching multiples in jsontemplate.py (PROJQUAY-0000) ([#800](https://github.com/quay/quay/issues/800))
### Util
- [230fd24f](https://github.com/quay/quay/commit/230fd24f3d3bb6b899442dfc6be1ffde8e30bc2c): Reading new UI feedback form url from config parameter (PROJQUAY-5463) ([#1902](https://github.com/quay/quay/issues/1902))
- [3035f46f](https://github.com/quay/quay/commit/3035f46f569bc46cd59ec1c7b63fe2cba35d0e04): Clean up and adding make target to install pre-commit hooks(PROJQUAY-000) ([#1587](https://github.com/quay/quay/issues/1587))
- [e8e5d5d9](https://github.com/quay/quay/commit/e8e5d5d90461cca38a4367be603ecdbb2fce956c): Adding git pre-commit checks (PROJQUAY-4658) ([#1585](https://github.com/quay/quay/issues/1585))
### Util.Canonicaljson
- [5bf41f9a](https://github.com/quay/quay/commit/5bf41f9a8d1b2c4e2e3bb1598649b7644daf7d68): add a kwarg for list ordering
### Util/Ipresolver
- [9ee1c580](https://github.com/quay/quay/commit/9ee1c580599eb74b83e16fc34f1fea369e2d0d66): manually add aws-ip-ranges.json ([#1065](https://github.com/quay/quay/issues/1065))
### Util/Metrics
- [1e8b15ef](https://github.com/quay/quay/commit/1e8b15ef0cae4fae65f81ce337ddf18ce1861ef0): use basename for processname
- [9755eb27](https://github.com/quay/quay/commit/9755eb27155f44d7c161087126883cfeabd91d2c): fix unqualified identifier
- [6a83a52c](https://github.com/quay/quay/commit/6a83a52cad496e57a8059ebbe70abf1bcd6de117): log groupkey and add more host data
- [2241d669](https://github.com/quay/quay/commit/2241d6693b6e0c8d2efa7acd62a5fb086819c028): add process based grouping key
- [5b3db536](https://github.com/quay/quay/commit/5b3db536ef37d4383beba0a572b7d22abe70e0f7): remove metricqueue abstraction
### Utility
- [69777301](https://github.com/quay/quay/commit/6977730185710cec71ef39edc55b5d774bc278b4): Fixes backfillreplication script to use manifest blobs (PROJQUAY-2218) ([#826](https://github.com/quay/quay/issues/826))
### V2auth
- [fd9a6b2e](https://github.com/quay/quay/commit/fd9a6b2e606db6d20bb079f4c3a942e176f83a0c): Check for user before creating org (PROJQUAY-3766) ([#1315](https://github.com/quay/quay/issues/1315))
### Validation
- [4c0a37a4](https://github.com/quay/quay/commit/4c0a37a4a2c44723ac5fd07d9e1f44577e2c9d66): calls to gcs should always be secure (PROJQUAY-2722) ([#131](https://github.com/quay/quay/issues/131))
- [04973cc1](https://github.com/quay/quay/commit/04973cc13ba89142100898fb4ed827a9452189e5): fix postgres root cert validation (PROJQUAY-2414) ([#113](https://github.com/quay/quay/issues/113))
### Validator
- [c4a3b5db](https://github.com/quay/quay/commit/c4a3b5db3771b0f32b5ad0c3a6e19723ed028124): Fix database.pem path in config.yaml (PROJQIUAY-4222) ([#181](https://github.com/quay/quay/issues/181))
- [75c713c7](https://github.com/quay/quay/commit/75c713c7ef7b08f59c7dff649e5c87efba580452): Use user provided endpoint for Gitlab and Github OAuth validations (PROJQUAY-2560) ([#168](https://github.com/quay/quay/issues/168))
- [3bfe148b](https://github.com/quay/quay/commit/3bfe148b909e59132be99b9b329e07561d730720): Check for IAM role when aws keys missing. (PROJQUAY-1626) ([#109](https://github.com/quay/quay/issues/109))
### Validators
- [f4fd536f](https://github.com/quay/quay/commit/f4fd536fc38dae19bd1baac6eb32d24f7ca5af4a): Remove cloudfront API calls that may not be included in policy (PROJQUAY-0000)
### Verbs
- [351535fa](https://github.com/quay/quay/commit/351535fa1adabb687d802522dd89f3c6f03ad92e): time blueprint
### Workflows
- [9ce9a671](https://github.com/quay/quay/commit/9ce9a6710598853f21945a56cab089b288938ad1): use tox from requirements
### [PROJQUAY-1021] Task
- [bd7252c5](https://github.com/quay/quay/commit/bd7252c536bcf8c49cca167d7c4b433489d36044): Update "Black" to version 20.8b1
### [PROJQUAY-1035] Fix
- [fbf5efb1](https://github.com/quay/quay/commit/fbf5efb1ec9751655d70f7e30125459a65432cff): Convert gunicorn worker counts to int for comparisons. ([#542](https://github.com/quay/quay/issues/542))
### [PROJQUAY-1149] Fix: Use Mysql+Pymysql
- [8cac4e77](https://github.com/quay/quay/commit/8cac4e7702a26c2d74b919a27db606c3398bfdc9): // for MySQL DB_URI
### [PROJQUAY-1190] Fix
- [9ccb3ea9](https://github.com/quay/quay/commit/9ccb3ea9b2f8e1aa0510e632c7897d2589314cda): Use Python3 strings for user-facing tokens ([#589](https://github.com/quay/quay/issues/589))
### [PROJQUAY-1191] Add
- [b3d4d8cc](https://github.com/quay/quay/commit/b3d4d8cc7669b7c42f9d4b31ac7094ca4cf566d2): log sent emails (debug) ([#594](https://github.com/quay/quay/issues/594))
### [PROJQUAY-822] Security
- [52b86ac9](https://github.com/quay/quay/commit/52b86ac9fdaed00bd30d95af685233a0c4b77c0a): Hide sensitive LDAP log data ([#562](https://github.com/quay/quay/issues/562))
### [PROJQUAY-833] Chore
- [3a0b5d3c](https://github.com/quay/quay/commit/3a0b5d3c48f724eb35d5630a7accc7daad7a2d66): Update Pillow to 7.2.0 ([#538](https://github.com/quay/quay/issues/538))
### [PROJQUAY-879] Fix
- [4d0581e2](https://github.com/quay/quay/commit/4d0581e2d9b12b8c0a096d8243eba380d7c88e88): Schema migrations with MySQL and SSL ([#596](https://github.com/quay/quay/issues/596))
### [Redhat-3.9] Api
- [a7555f48](https://github.com/quay/quay/commit/a7555f4813a62cf2e88a5b7fb58828ad6fe11303): fix duplicate robot accounts (PROJQUAY-5931) ([#2198](https://github.com/quay/quay/issues/2198))
- [1239477f](https://github.com/quay/quay/commit/1239477f546e2be0ccebbc10712701d2d207dd4f): Adding ignore timezone flag when parsing datetime (PROJQUAY-5360) ([#2079](https://github.com/quay/quay/issues/2079))
- [2afab1c6](https://github.com/quay/quay/commit/2afab1c67473cfa7cfa16878705b55c905b20625): add permanently delete tag usage log (PROJQUAY-5496) ([#1926](https://github.com/quay/quay/issues/1926))
### [Redhat-3.9] Authentication(LDAP)
- [6be4d052](https://github.com/quay/quay/commit/6be4d052ff8a841d35dbfd69fe7bfdf674302ace): allow LDAP referrals to not be followed (PROJQUAY-5291)  ([#1922](https://github.com/quay/quay/issues/1922))
### [Redhat-3.9] Build(Deps)
- [1d08b96b](https://github.com/quay/quay/commit/1d08b96bd41b33e4dee74887cb4632d04cea2bb9): bump jquery from 1.12.4 to 3.5.0 in /config-tool/pkg/lib/editor ([#3667](https://github.com/quay/quay/issues/3667))
- [db00f7f7](https://github.com/quay/quay/commit/db00f7f7713071879a10f86d4d5b0707962dfe19): bump cypress from 10.10.0 to 12.17.4 in /web ([#2308](https://github.com/quay/quay/issues/2308))
- [648f9571](https://github.com/quay/quay/commit/648f9571e3a241be638929c66b2012f78a2ee201): bump golang.org/x/net (PROJQUAY-5339) ([#2093](https://github.com/quay/quay/issues/2093))
### [Redhat-3.9] Chore
- [db489488](https://github.com/quay/quay/commit/db489488652da347ca371bca943e6fa3c7078116): update werkzeug and related package versions (PROJQUAY-5098) ([#3570](https://github.com/quay/quay/issues/3570))
- [30132066](https://github.com/quay/quay/commit/30132066e32a462489dd5c0466e2c1efe43b387c): remove husky ([#2307](https://github.com/quay/quay/issues/2307))
- [2032ffa7](https://github.com/quay/quay/commit/2032ffa742492c96050f4f3f710c5780f6195a53): pull changes for s390x from master ([#2107](https://github.com/quay/quay/issues/2107))
### [Redhat-3.9] Dep
- [f44ac01b](https://github.com/quay/quay/commit/f44ac01b259b15187df0b920ae325cbca4226807): upgrading actions/download-artifact to v4 (PROJQUAY-8379) ([#3535](https://github.com/quay/quay/issues/3535))
### [Redhat-3.9] Georeplication
- [7152164c](https://github.com/quay/quay/commit/7152164c87b816a02b2d2689a0329f146a552e38): Enqueue blobs for replication on manifest list pushes (PROJQUAY-5256) ([#2232](https://github.com/quay/quay/issues/2232))
### [Redhat-3.9] Oci
- [0f8fd65d](https://github.com/quay/quay/commit/0f8fd65d2ccd0c1a4248aab20a25bbdb5c92367a): Allow optional components in the image config to be set to "null" (PROJQUAY-5634) ([#1964](https://github.com/quay/quay/issues/1964))
### [Redhat-3.9] Pagination
- [81dc7966](https://github.com/quay/quay/commit/81dc79668c5223deb9edeaf5710cc9ef30bd5b78): Fixing paginate for /api/v1/superuser/logs API (PROJQUAY-5360) ([#2011](https://github.com/quay/quay/issues/2011))
### [Redhat-3.9] Reconfigure
- [8b47d3fd](https://github.com/quay/quay/commit/8b47d3fdd580737ca9a676ffbbfe3cdf3e451d21): Remove ca-bundle.crt and service-ca.crt (PROJQUAY-5233) ([#2257](https://github.com/quay/quay/issues/2257))
### [Redhat-3.9] Storage
- [a6776d94](https://github.com/quay/quay/commit/a6776d940c497c75948e436504d2ae2f065fe41f): adding maximum_chunk_size_gb storage option (PROJQUAY-2679) ([#2191](https://github.com/quay/quay/issues/2191))
- [313a9544](https://github.com/quay/quay/commit/313a95444b010159ddef3ce7446279852b177441): make cloudfront_distribution_org_overrides optional (PROJQUAY-5788) ([#2009](https://github.com/quay/quay/issues/2009))
### [Redhat-3.9] UI
- [b1bab0b9](https://github.com/quay/quay/commit/b1bab0b93dc734d5fd7b537030289540c7ed9bf3): Replace time to wait with event waits in cypress tests ([#2078](https://github.com/quay/quay/issues/2078))
### [Redhat-3.9] Ui
- [02d6f64e](https://github.com/quay/quay/commit/02d6f64ee79b94de4ebc35c703d621753d3f1880): removing bootbox ([#3505](https://github.com/quay/quay/issues/3505))
- [a659db25](https://github.com/quay/quay/commit/a659db25ec67a2237205ebb3c4a33c20cf61adf4): Robot Accounts tab fixes (PROJQUAY-5914) ([#2135](https://github.com/quay/quay/issues/2135))
- [7f54e765](https://github.com/quay/quay/commit/7f54e76599eec683633e16514a390ec9db61129c): displaying quota totals on user namespaces (PROJQUAY-5581) ([#2128](https://github.com/quay/quay/issues/2128))
- [fcdb292a](https://github.com/quay/quay/commit/fcdb292a47653c97291f703da3c24ad756c5628e): display sizes as base 2  (PROJQUAY-5524) ([#1970](https://github.com/quay/quay/issues/1970))
### Reverts
- Revert "Remove the active migration for encrypted tokens now that it is complete"
- Remove the active migration for encrypted tokens now that it is complete

### Pull Requests
- Merge pull request [#2069](https://github.com/quay/quay/issues/2069) from dmage/merge-config-tool-3.9
- Merge pull request [#108](https://github.com/quay/quay/issues/108) from quay/PROJQUAY-1998
- Merge pull request [#107](https://github.com/quay/quay/issues/107) from quay/PROJQUAY-1815
- Merge pull request [#104](https://github.com/quay/quay/issues/104) from syed/add-redis-ssl
- Merge pull request [#106](https://github.com/quay/quay/issues/106) from quay/loggin_refactor
- Merge pull request [#105](https://github.com/quay/quay/issues/105) from quay/scram_fix
- Merge pull request [#100](https://github.com/quay/quay/issues/100) from alecmerdler/PROJQUAY-1610
- Merge pull request [#99](https://github.com/quay/quay/issues/99) from quay/PROJQUAY-1963
- Merge pull request [#98](https://github.com/quay/quay/issues/98) from quay/PROJQUAY-1964
- Merge pull request [#97](https://github.com/quay/quay/issues/97) from quay/ensure_mail_tls_fips
- Merge pull request [#95](https://github.com/quay/quay/issues/95) from thomasmckay/1925-config-download
- Merge pull request [#93](https://github.com/quay/quay/issues/93) from alecmerdler/oidc-tls-client
- Merge pull request [#90](https://github.com/quay/quay/issues/90) from kleesc/set-correct-userfiles-location-default
- Merge pull request [#87](https://github.com/quay/quay/issues/87) from thomasmckay/1633-secret-key
- Merge pull request [#83](https://github.com/quay/quay/issues/83) from alecmerdler/PROJQUAY-1577
- Merge pull request [#80](https://github.com/quay/quay/issues/80) from quay/aioi_gen
- Merge pull request [#82](https://github.com/quay/quay/issues/82) from quay/PROJQUAY-1561
- Merge pull request [#78](https://github.com/quay/quay/issues/78) from quay/PROJQUAY-1270
- Merge pull request [#77](https://github.com/quay/quay/issues/77) from quay/PROJQUAY-1262
- Merge pull request [#76](https://github.com/quay/quay/issues/76) from quay/PROJQUAY-541
- Merge pull request [#74](https://github.com/quay/quay/issues/74) from quay/vendor
- Merge pull request [#72](https://github.com/quay/quay/issues/72) from alecmerdler/PROJQUAY-1306
- Merge pull request [#70](https://github.com/quay/quay/issues/70) from quay/oidc
- Merge pull request [#69](https://github.com/quay/quay/issues/69) from quay/mail_validate
- Merge pull request [#68](https://github.com/quay/quay/issues/68) from quay/swiftV3
- Merge pull request [#67](https://github.com/quay/quay/issues/67) from quay/fix_file_input
- Merge pull request [#66](https://github.com/quay/quay/issues/66) from quay/remove_boolean_omitempty
- Merge pull request [#65](https://github.com/quay/quay/issues/65) from quay/fix_modals
- Merge pull request [#64](https://github.com/quay/quay/issues/64) from quay/swift_validation
- Merge pull request [#63](https://github.com/quay/quay/issues/63) from quay/ldap_query
- Merge pull request [#62](https://github.com/quay/quay/issues/62) from quay/feature_sign
- Merge pull request [#61](https://github.com/quay/quay/issues/61) from quay/cert_port
- Merge pull request [#60](https://github.com/quay/quay/issues/60) from quay/cloudfront
- Merge pull request [#59](https://github.com/quay/quay/issues/59) from quay/dbssl
- Merge pull request [#58](https://github.com/quay/quay/issues/58) from quay/fixjs
- Merge pull request [#56](https://github.com/quay/quay/issues/56) from quay/ldap
- Merge pull request [#55](https://github.com/quay/quay/issues/55) from quay/checkBucket
- Merge pull request [#54](https://github.com/quay/quay/issues/54) from alecmerdler/PROJQUAY-1156
- Merge pull request [#53](https://github.com/quay/quay/issues/53) from BillDett/PROJQUAY-1202
- Merge pull request [#52](https://github.com/quay/quay/issues/52) from quay/switchTLS
- Merge pull request [#51](https://github.com/quay/quay/issues/51) from quay/tls_timeout
- Merge pull request [#50](https://github.com/quay/quay/issues/50) from quay/azure
- Merge pull request [#49](https://github.com/quay/quay/issues/49) from quay/time_machine
- Merge pull request [#48](https://github.com/quay/quay/issues/48) from thomasmckay/1198-deprecated
- Merge pull request [#47](https://github.com/quay/quay/issues/47) from quay/storage_fix
- Merge pull request [#46](https://github.com/quay/quay/issues/46) from quay/cert_fix
- Merge pull request [#45](https://github.com/quay/quay/issues/45) from quay/fix_mail
- Merge pull request [#41](https://github.com/quay/quay/issues/41) from kurtismullins/PROJQUAY-1149
- Merge pull request [#44](https://github.com/quay/quay/issues/44) from quay/gitlab_endpoint
- Merge pull request [#43](https://github.com/quay/quay/issues/43) from quay/tar2
- Merge pull request [#42](https://github.com/quay/quay/issues/42) from quay/clean_dev_env
- Merge pull request [#40](https://github.com/quay/quay/issues/40) from quay/storage_fix
- Merge pull request [#39](https://github.com/quay/quay/issues/39) from quay/debug
- Merge pull request [#38](https://github.com/quay/quay/issues/38) from quay/super_users
- Merge pull request [#37](https://github.com/quay/quay/issues/37) from quay/setup_add_vars
- Merge pull request [#36](https://github.com/quay/quay/issues/36) from quay/clair_setup
- Merge pull request [#29](https://github.com/quay/quay/issues/29) from quay/security_scanner_psk
- Merge pull request [#34](https://github.com/quay/quay/issues/34) from quay/omitempty
- Merge pull request [#35](https://github.com/quay/quay/issues/35) from quay/warn_no_mount
- Merge pull request [#33](https://github.com/quay/quay/issues/33) from quay/cert_load_cli
- Merge pull request [#30](https://github.com/quay/quay/issues/30) from quay/add_nullfix_to_api
- Merge pull request [#31](https://github.com/quay/quay/issues/31) from quay/postgres_pg_check
- Merge pull request [#32](https://github.com/quay/quay/issues/32) from alecmerdler/PROJQUAY-1107
- Merge pull request [#28](https://github.com/quay/quay/issues/28) from quay/tls
- Merge pull request [#27](https://github.com/quay/quay/issues/27) from quay/localstorage_fix
- Merge pull request [#26](https://github.com/quay/quay/issues/26) from quay/chi_migration
- Merge pull request [#24](https://github.com/quay/quay/issues/24) from alecmerdler/distributedstorage-proxy
- Merge pull request [#23](https://github.com/quay/quay/issues/23) from alecmerdler/PROJQUAY-909
- Merge pull request [#14](https://github.com/quay/quay/issues/14) from thomasmckay/npm
- Merge pull request [#21](https://github.com/quay/quay/issues/21) from alecmerdler/distributedstorage-unmarshal
- Merge pull request [#19](https://github.com/quay/quay/issues/19) from alecmerdler/PROJQUAY-1064
- Merge pull request [#18](https://github.com/quay/quay/issues/18) from quay/repo_mirror
- Merge pull request [#16](https://github.com/quay/quay/issues/16) from alecmerdler/PROJQUAY-909
- Merge pull request [#17](https://github.com/quay/quay/issues/17) from alecmerdler/PROJQUAY-1029
- Merge pull request [#15](https://github.com/quay/quay/issues/15) from quay/remove-hardcoded-conf-path
- Merge pull request [#13](https://github.com/quay/quay/issues/13) from quay/fileUploads
- Merge pull request [#11](https://github.com/quay/quay/issues/11) from josephschorr/config-editor
- Merge pull request [#10](https://github.com/quay/quay/issues/10) from alecmerdler/pull-request-template
- Merge pull request [#9](https://github.com/quay/quay/issues/9) from alecmerdler/fix-json-tags-hostsettings
- Merge pull request [#8](https://github.com/quay/quay/issues/8) from alecmerdler/distributedstorage-omitempty
- Merge pull request [#7](https://github.com/quay/quay/issues/7) from alecmerdler/dbconnectionargs-omitempty
- Merge pull request [#6](https://github.com/quay/quay/issues/6) from alecmerdler/json-tags
- Merge pull request [#5](https://github.com/quay/quay/issues/5) from alecmerdler/distributedstorage-fieldgroup
- Merge pull request [#4](https://github.com/quay/quay/issues/4) from alecmerdler/securityscanner-typefix
- Merge pull request [#3](https://github.com/quay/quay/issues/3) from quay/remove_validate_dep
- Merge pull request [#2](https://github.com/quay/quay/issues/2) from quay/remove_validate_dep
- Merge pull request [#1](https://github.com/quay/quay/issues/1) from quay/new_schema
- Merge pull request [#304](https://github.com/quay/quay/issues/304) from jzelinskie/workflows
- Merge pull request [#236](https://github.com/quay/quay/issues/236) from alecmerdler/fix-local-config-app
- Merge pull request [#232](https://github.com/quay/quay/issues/232) from josephschorr/joseph.schorr/PROJQUAY-268/github-params
- Merge pull request [#227](https://github.com/quay/quay/issues/227) from josephschorr/joseph.schorr/PROJQUAY-220/tag-history-future
- Merge pull request [#230](https://github.com/quay/quay/issues/230) from josephschorr/joseph.schorr/PROJQUAY-268/upgrade-github-lib
- Merge pull request [#28](https://github.com/quay/quay/issues/28) from sghosh151/master
- Merge pull request [#224](https://github.com/quay/quay/issues/224) from jzelinskie/route-buckets
- Merge pull request [#229](https://github.com/quay/quay/issues/229) from jzelinskie/verb-blueprint-metrics
- Merge pull request [#221](https://github.com/quay/quay/issues/221) from josephschorr/fix-v2-labels
- Merge pull request [#220](https://github.com/quay/quay/issues/220) from josephschorr/joseph.schorr/PROJQUAY-227/manifest-conversion
- Merge pull request [#228](https://github.com/quay/quay/issues/228) from josephschorr/fix-repo-gc-timeout
- Merge pull request [#226](https://github.com/quay/quay/issues/226) from josephschorr/joseph.schorr/PROJQUAY-289/repo-create-error
- Merge pull request [#180](https://github.com/quay/quay/issues/180) from alecmerdler/fix-docstrings
- Merge pull request [#215](https://github.com/quay/quay/issues/215) from josephschorr/joseph.schorr/PROJQUAY-239/repo-gc-timeout-fix
- Merge pull request [#134](https://github.com/quay/quay/issues/134) from josephschorr/joseph.schorr/QUAY-1747/better-tagging
- Merge pull request [#214](https://github.com/quay/quay/issues/214) from josephschorr/add-v22-namespace-blacklist
- Merge pull request [#212](https://github.com/quay/quay/issues/212) from josephschorr/extra-storage-verification
- Merge pull request [#213](https://github.com/quay/quay/issues/213) from josephschorr/secscan-v2-tests
- Merge pull request [#211](https://github.com/quay/quay/issues/211) from josephschorr/manifest-config-blob-fixes
- Merge pull request [#209](https://github.com/quay/quay/issues/209) from josephschorr/fix-secscan-model
- Merge pull request [#208](https://github.com/quay/quay/issues/208) from josephschorr/joseph.schorr/PROJQUAY-219/better-manifest-errors
- Merge pull request [#175](https://github.com/quay/quay/issues/175) from josephschorr/joseph.schorr/PROJQUAY-177/abstract-sec-api
- Merge pull request [#205](https://github.com/quay/quay/issues/205) from josephschorr/add-build-badge
- Merge pull request [#119](https://github.com/quay/quay/issues/119) from josephschorr/joseph.schorr/PROJQUAY-124/async-repo-delete
- Merge pull request [#202](https://github.com/quay/quay/issues/202) from josephschorr/fix-robot-backfill
- Merge pull request [#200](https://github.com/quay/quay/issues/200) from thomasmckay/66-cherry-pick-changelog
- Merge pull request [#199](https://github.com/quay/quay/issues/199) from quay/revert-187-revert-181-joseph.schorr/PROJQUAY-185/remove-enc-token
- Merge pull request [#168](https://github.com/quay/quay/issues/168) from josephschorr/joseph.schorr/PROJQUAY-178/label-fixes
- Merge pull request [#194](https://github.com/quay/quay/issues/194) from tparikh/fix-debug-param
- Merge pull request [#187](https://github.com/quay/quay/issues/187) from quay/revert-181-joseph.schorr/PROJQUAY-185/remove-enc-token
- Merge pull request [#189](https://github.com/quay/quay/issues/189) from tparikh/PROJQUAY-181-fix-formatting
- Merge pull request [#184](https://github.com/quay/quay/issues/184) from tparikh/PROJQUAY-181
- Merge pull request [#170](https://github.com/quay/quay/issues/170) from alecmerdler/duplicate-secscan-code
- Merge pull request [#181](https://github.com/quay/quay/issues/181) from josephschorr/joseph.schorr/PROJQUAY-185/remove-enc-token
- Merge pull request [#182](https://github.com/quay/quay/issues/182) from josephschorr/joseph.schorr/PROJQUAY-186/fix-bitbucket-trigger-creation
- Merge pull request [#174](https://github.com/quay/quay/issues/174) from tparikh/http-redirect
- Merge pull request [#172](https://github.com/quay/quay/issues/172) from kurtismullins/fix-broken-ci
- Merge pull request [#169](https://github.com/quay/quay/issues/169) from jzelinskie/prom-route
- Merge pull request [#165](https://github.com/quay/quay/issues/165) from cclauss/patch-3
- Merge pull request [#162](https://github.com/quay/quay/issues/162) from cclauss/patch-2
- Merge pull request [#161](https://github.com/quay/quay/issues/161) from jzelinskie/prom-docs
- Merge pull request [#163](https://github.com/quay/quay/issues/163) from josephschorr/joseph.schorr/PROJQUAY-170/appr-limits
- Merge pull request [#158](https://github.com/quay/quay/issues/158) from josephschorr/joseph.schjorr/PROJQUAY-168/fix-migration
- Merge pull request [#164](https://github.com/quay/quay/issues/164) from alecmerdler/PROJQUAY-171
- Merge pull request [#49](https://github.com/quay/quay/issues/49) from quay/dependabot/pip/ecdsa-0.13.3
- Merge pull request [#135](https://github.com/quay/quay/issues/135) from quay/dependabot/pip/waitress-1.4.2
- Merge pull request [#151](https://github.com/quay/quay/issues/151) from josephschorr/fix-notification-view
- Merge pull request [#150](https://github.com/quay/quay/issues/150) from thomasmckay/146-fix-osbs
- Merge pull request [#149](https://github.com/quay/quay/issues/149) from kurtismullins/fix-setuptools-in-dockerfile
- Merge pull request [#145](https://github.com/quay/quay/issues/145) from kurtismullins/QUAY-1748
- Merge pull request [#110](https://github.com/quay/quay/issues/110) from jzelinskie/consistent-metrics
- Merge pull request [#132](https://github.com/quay/quay/issues/132) from josephschorr/joseph.schorr/QUAY-2239/fix-log-lookup
- Merge pull request [#142](https://github.com/quay/quay/issues/142) from josephschorr/joseph.schorr/PROJQUAY-132/queuefile-timeout
- Merge pull request [#144](https://github.com/quay/quay/issues/144) from MrDevJay/master
- Merge pull request [#121](https://github.com/quay/quay/issues/121) from josephschorr/joseph.schorr/QUAY-2100/gitlab-500
- Merge pull request [#120](https://github.com/quay/quay/issues/120) from josephschorr/joseph.schorr/PROJQUAY-125/fix-migration-template
- Merge pull request [#133](https://github.com/quay/quay/issues/133) from josephschorr/joseph.schorr/PROJQUAY-129/label-links
- Merge pull request [#140](https://github.com/quay/quay/issues/140) from tparikh/elb-proxy-protocol
- Merge pull request [#109](https://github.com/quay/quay/issues/109) from josephschorr/joseph.schorr/QUAY-1322/custom-webhook-body
- Merge pull request [#127](https://github.com/quay/quay/issues/127) from josephschorr/joseph.schorr/QUAY-2111/created-datetime
- Merge pull request [#122](https://github.com/quay/quay/issues/122) from josephschorr/joseph.schorr/PROJQUAY-126/digest-500
- Merge pull request [#114](https://github.com/quay/quay/issues/114) from tparikh/projquay117
- Merge pull request [#108](https://github.com/quay/quay/issues/108) from josephschorr/joseph.schorr/QUAY-1312/fresh-login-fix
- Merge pull request [#96](https://github.com/quay/quay/issues/96) from alecmerdler/QUAY-2213
- Merge pull request [#107](https://github.com/quay/quay/issues/107) from jzelinskie/job-status-str
- Merge pull request [#105](https://github.com/quay/quay/issues/105) from tparikh/drop-extra-ca-certs-dir
- Merge pull request [#106](https://github.com/quay/quay/issues/106) from tparikh/find-symlinks-ca-certs
- Merge pull request [#104](https://github.com/quay/quay/issues/104) from tparikh/update-quay-extra-certs-path
- Merge pull request [#100](https://github.com/quay/quay/issues/100) from thomasmckay/92-black
- Merge pull request [#98](https://github.com/quay/quay/issues/98) from tparikh/projquay67-fix-port
- Merge pull request [#92](https://github.com/quay/quay/issues/92) from tparikh/projquay67
- Merge pull request [#95](https://github.com/quay/quay/issues/95) from jzelinskie/consolidate-openshift
- Merge pull request [#94](https://github.com/quay/quay/issues/94) from jzelinskie/monitoring-template
- Merge pull request [#89](https://github.com/quay/quay/issues/89) from jzelinskie/prom-port
- Merge pull request [#79](https://github.com/quay/quay/issues/79) from josephschorr/joseph.schorr/QUAY-2225/reencrypt-fields
- Merge pull request [#88](https://github.com/quay/quay/issues/88) from josephschorr/joseph.schorr/PROJQUAY-62/deprecation
- Merge pull request [#87](https://github.com/quay/quay/issues/87) from quay/logforward
- Merge pull request [#80](https://github.com/quay/quay/issues/80) from josephschorr/joseph.schorr/QUAY-2204/fix-et-phase-2
- Merge pull request [#84](https://github.com/quay/quay/issues/84) from josephschorr/joseph.schorr/PROJQUAY-63/fix-count-repo-actions
- Merge pull request [#76](https://github.com/quay/quay/issues/76) from thomasmckay/58-tech-preview
- Merge pull request [#77](https://github.com/quay/quay/issues/77) from thomasmckay/59-rhocs
- Merge pull request [#78](https://github.com/quay/quay/issues/78) from tparikh/mount-quay-extra-ca-certs
- Merge pull request [#71](https://github.com/quay/quay/issues/71) from alecmerdler/QUAY-2201
- Merge pull request [#68](https://github.com/quay/quay/issues/68) from alecmerdler/PROJQUAY-6-redux
- Merge pull request [#69](https://github.com/quay/quay/issues/69) from tparikh/add-metrics-port-clusterip-svc
- Merge pull request [#70](https://github.com/quay/quay/issues/70) from jzelinskie/basename-prom
- Merge pull request [#67](https://github.com/quay/quay/issues/67) from alecmerdler/QUAY-2213
- Merge pull request [#63](https://github.com/quay/quay/issues/63) from thomasmckay/53-mirror-token
- Merge pull request [#66](https://github.com/quay/quay/issues/66) from jzelinskie/qualified
- Merge pull request [#65](https://github.com/quay/quay/issues/65) from tparikh/projquay-39
- Merge pull request [#64](https://github.com/quay/quay/issues/64) from jzelinskie/prom-log-groupkey
- Merge pull request [#62](https://github.com/quay/quay/issues/62) from jzelinskie/prom-grouping
- Merge pull request [#58](https://github.com/quay/quay/issues/58) from alecmerdler/PROJQUAY-6
- Merge pull request [#60](https://github.com/quay/quay/issues/60) from jzelinskie/debug-pushgateway
- Merge pull request [#59](https://github.com/quay/quay/issues/59) from jzelinskie/prom-osbs
- Merge pull request [#22](https://github.com/quay/quay/issues/22) from jzelinskie/prometheus-redo
- Merge pull request [#54](https://github.com/quay/quay/issues/54) from alecmerdler/PROJQUAY-42
- Merge pull request [#51](https://github.com/quay/quay/issues/51) from josephschorr/break-et-phases
- Merge pull request [#50](https://github.com/quay/quay/issues/50) from thomasmckay/40-azure-versions
- Merge pull request [#34](https://github.com/quay/quay/issues/34) from alecmerdler/PROJQUAY-6
- Merge pull request [#48](https://github.com/quay/quay/issues/48) from josephschorr/joseph.schorr/PROJQUAY-37/out-of-bounds
- Merge pull request [#46](https://github.com/quay/quay/issues/46) from quay/joseph.schorr/PROJQUAY-35/fix-gitlab-deactivate
- Merge pull request [#47](https://github.com/quay/quay/issues/47) from thomasmckay/34-root-certs
- Merge pull request [#41](https://github.com/quay/quay/issues/41) from thomasmckay/black
- Merge pull request [#45](https://github.com/quay/quay/issues/45) from maorfr/post-deploy
- Merge pull request [#44](https://github.com/quay/quay/issues/44) from josephschorr/noop-fix
- Merge pull request [#42](https://github.com/quay/quay/issues/42) from josephschorr/fix-access-token-clear
- Merge pull request [#43](https://github.com/quay/quay/issues/43) from jzelinskie/ci-logs
- Merge pull request [#40](https://github.com/quay/quay/issues/40) from tparikh/rhel7-base-img-src
- Merge pull request [#33](https://github.com/quay/quay/issues/33) from thomasmckay/18-travis-branches
- Merge pull request [#35](https://github.com/quay/quay/issues/35) from vbatts/mailing-list
- Merge pull request [#39](https://github.com/quay/quay/issues/39) from tparikh/refactor-app-sre-scripts-2
- Merge pull request [#37](https://github.com/quay/quay/issues/37) from tparikh/quay-openshift-template-updates
- Merge pull request [#36](https://github.com/quay/quay/issues/36) from tparikh/quay-openshift-deployment-updates
- Merge pull request [#32](https://github.com/quay/quay/issues/32) from thomasmckay/20-non-root
- Merge pull request [#21](https://github.com/quay/quay/issues/21) from alecmerdler/opensearch
- Merge pull request [#25](https://github.com/quay/quay/issues/25) from thomasmckay/12-mirror-api
- Merge pull request [#26](https://github.com/quay/quay/issues/26) from tparikh/fix-openshift-deployment
- Merge pull request [#24](https://github.com/quay/quay/issues/24) from tparikh/quayio-osd-deployment
- Merge pull request [#20](https://github.com/quay/quay/issues/20) from josephschorr/fix-alembic-no-migration
- Merge pull request [#17](https://github.com/quay/quay/issues/17) from josephschorr/fix-encrypted-token-migration
- Merge pull request [#18](https://github.com/quay/quay/issues/18) from josephschorr/remove-email-viewer-tool
- Merge pull request [#16](https://github.com/quay/quay/issues/16) from tparikh/app-sre-pipeline-integration
- Merge pull request [#13](https://github.com/quay/quay/issues/13) from kbrwn/nginx-storage-proxy-header-fix
- Merge pull request [#14](https://github.com/quay/quay/issues/14) from danielhelfand/dtr_broken_link
- Merge pull request [#12](https://github.com/quay/quay/issues/12) from jzelinskie/jboss-jira
- Merge pull request [#11](https://github.com/quay/quay/issues/11) from alecmerdler/PROJQUAY-3
- Merge pull request [#1](https://github.com/quay/quay/issues/1) from quay/init


[Unreleased]: https://github.com/quay/quay/compare/v3.9.11...HEAD
## Historical Changelog
[CHANGELOG.md](https://github.com/quay/quay/blob/96b17b8338fb10ca2ed12e9bc920dcbba148289c/CHANGELOG.md)
