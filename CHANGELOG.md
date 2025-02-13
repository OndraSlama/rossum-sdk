# CHANGELOG



## v0.8.0 (2023-08-11)

### Feature

* feat(models): add token_lifetime_s attribute to hook model ([`f75dcfd`](https://github.com/rossumai/rossum-sdk/commit/f75dcfd5d346edadef9e56532316b217d069fbbb))

### Unknown

* Merge pull request #48 from uhlikfil/main

feat(models): add token_lifetime_s attribute to hook model ([`ae35fc4`](https://github.com/rossumai/rossum-sdk/commit/ae35fc4e6ae269389904e0df88df548fab67d9e4))


## v0.7.3 (2023-08-07)

### Fix

* fix: Make time_spent in Annotation optional ([`a2e5d70`](https://github.com/rossumai/rossum-sdk/commit/a2e5d70a777b2c2fb0fc77b78eb005311cd36853))

### Unknown

* Merge pull request #47 from rossumai/ihe/make-time-spent-optional

fix: Make time_spent in Annotation optional ([`7a26f27`](https://github.com/rossumai/rossum-sdk/commit/7a26f2753514a50313a9f1c038fdbd955689d1fb))


## v0.7.2 (2023-06-02)

### Fix

* fix: add await to asyncio.sleep ([`4a537ab`](https://github.com/rossumai/rossum-sdk/commit/4a537ab6641e7745383a45dba7dd77bc0d6eb28c))

### Unknown

* Merge pull request #46 from uhlikfil/main

await asyncio.sleep ([`3183975`](https://github.com/rossumai/rossum-sdk/commit/318397584681cc74862909ca69dcd9f4b9959832))


## v0.7.1 (2023-05-05)

### Fix

* fix(models): allow null workspace in Queue model ([`dea0027`](https://github.com/rossumai/rossum-sdk/commit/dea00275c23d8b121ad29c1e624e74431923a4b0))

* fix(models): allow Any in metadata dict values in Queue model ([`7abaa13`](https://github.com/rossumai/rossum-sdk/commit/7abaa135a5f5f30f6e001afa9d22258dc89fcbc1))

### Unknown

* Merge pull request #45 from uhlikfil/filda/fix-queue-model-metadata

fix(models): make queue model compliant with API docs ([`99e180c`](https://github.com/rossumai/rossum-sdk/commit/99e180c7bd966d4ecae23b6713bfa341cfc9ce47))


## v0.7.0 (2023-05-04)

### Feature

* feat(elis_api_client): add generic method for requests to paginated resources ([`6b290e8`](https://github.com/rossumai/rossum-sdk/commit/6b290e8cb340f7be81768b311678163a3bfc41a8))

### Unknown

* Merge pull request #44 from OndraSlama/ondra/add-new-method-for-paginated-requests

feat(elis_api_client): add generic method for requests to paginated resources ([`7fc08c1`](https://github.com/rossumai/rossum-sdk/commit/7fc08c1e9251a9a135588003583af3b329f55bfc))


## v0.6.0 (2023-04-28)

### Chore

* chore: run test workflow also on pull requests ([`0ca9b43`](https://github.com/rossumai/rossum-sdk/commit/0ca9b43a555fbf3e238867a538e1459581351a74))

### Feature

* feat(api_client): allow to set max pages limit in filters ([`090114f`](https://github.com/rossumai/rossum-sdk/commit/090114fbaecc3d84706715e80f119e623882826a))

### Unknown

* Merge pull request #42 from OndraSlama/ondra/add-option-to-limit-number-of-pages

feat(api_client): allow to set max pages limit in filters ([`9b47c1d`](https://github.com/rossumai/rossum-sdk/commit/9b47c1da6bb0304be8bf99301427e458b7d0ba68))

* Merge pull request #43 from rossumai/oh/gh-actions-on-pull-request

chore: run test workflow also on pull requests ([`2f9efc3`](https://github.com/rossumai/rossum-sdk/commit/2f9efc3ac48107a4950555fd695e345722b723a7))


## v0.5.1 (2023-03-31)

### Chore

* chore: fix semantic release ([`f1e56a5`](https://github.com/rossumai/rossum-sdk/commit/f1e56a57ac9d0210b5e3258ae71d63950c5598d1))

### Fix

* fix: switch from TravisCI to Github Workflows ([`de09e69`](https://github.com/rossumai/rossum-sdk/commit/de09e698f20c587932d5ad050d68f96e043ad645))

### Unknown

* Use ruff for linting :tada: ([`27f9eea`](https://github.com/rossumai/rossum-sdk/commit/27f9eeafa81ed844be50aa306a01401b1b557f1f))

* Create lint-and-test.yml ([`1492b4b`](https://github.com/rossumai/rossum-sdk/commit/1492b4ba4dd791f0c8aa477e2cbb59877d05e734))


## v0.5.0 (2023-03-06)

### Feature

* feat(rossum_sdk/api_client): add `request` method to ElisApiClient ([`5d11c3e`](https://github.com/rossumai/rossum-sdk/commit/5d11c3e5e70e22f2875787b8ee960b8184ddb99d))

### Unknown

* Merge pull request #38 from OndraSlama/ondra/add-request-method-to-ElisApiClient

feat(rossum_sdk/api_client): add `request` method to ElisApiClient ([`b7ccf1e`](https://github.com/rossumai/rossum-sdk/commit/b7ccf1e8448eb29e3d03d2d3e8a38c22ade33464))


## v0.4.0 (2023-03-02)

### Chore

* chore: fix tests that started failing with pytest-httpx==0.21.2

The library no longer ignores missing empty URL parameters when matching
URLs. ([`da18d27`](https://github.com/rossumai/rossum-sdk/commit/da18d275eebc4f85af8a6c6f913f430e8e1b871c))

* chore: fix mypy installation in pre-commit by upgrading it

The old version installed a version of `types-ats` that caused a crash
during pre-commit installation. ([`5d4b387`](https://github.com/rossumai/rossum-sdk/commit/5d4b3870570cd7fcd82e86c8835246e7733e29ed))

* chore: run semrel only once ([`3b9392a`](https://github.com/rossumai/rossum-sdk/commit/3b9392ab7cbcbe049cc1c46d2ab434e5f0d5efd8))

* chore: do not run commitizen when there is no commit ([`4f534d5`](https://github.com/rossumai/rossum-sdk/commit/4f534d55f8b6dd1bd981c3fe8aa1c00c36af493e))

* chore: add pre-commit hook for commit messages ([`e641469`](https://github.com/rossumai/rossum-sdk/commit/e6414696a7cd9405978c2afd0a3aa050ee7fc9e6))

### Feature

* feat: add get_token method to Api client ([`a1bc957`](https://github.com/rossumai/rossum-sdk/commit/a1bc957540f84ba2ff0be7540d509a84580c1cef))

### Fix

* fix(models:hook): define some attributes (guide, read_more_url, extension_image_url) as optional ([`b16a456`](https://github.com/rossumai/rossum-sdk/commit/b16a456344b41908c16c32b4d5be70d31f3b07b3))

* fix: define `Document.creator` as optional (#35)

Co-authored-by: Ondrej Slama &lt;ondrej.slama@rossum.ai&gt; ([`d797e99`](https://github.com/rossumai/rossum-sdk/commit/d797e99112416602487409aaa668327fd80663aa))

### Unknown

* Merge pull request #36 from OndraSlama/ondra/fix-hook-annotation

fix(models:hook): define attributes `guide`, `read_more_url` and `extension_image_url` as optional ([`8020db1`](https://github.com/rossumai/rossum-sdk/commit/8020db1d29fce4c328e7b1a64fe5807d3d250a8d))

* Merge pull request #32 from rossumai/oh/fix-tests-after-pytest-httpx-upgrade

Fix failing mypy precommit hook and failing tests after pytest-httpx upgrade ([`65fb667`](https://github.com/rossumai/rossum-sdk/commit/65fb667b92a321edb012041674e527743f2ac3a6))

* Merge pull request #30 from rossumai/miiila/update-travis-for-semrel

Run semrel only once ([`204d334`](https://github.com/rossumai/rossum-sdk/commit/204d334664dc84b31437cc4f2fa3fc9d54cc9bb1))

* Merge pull request #29 from rossumai/mv/add-commitizen-pre-commit

chore: do not run commitizen when there is no commit ([`a98cd5a`](https://github.com/rossumai/rossum-sdk/commit/a98cd5a46f818ae6b6383ee175391d10ae967ebf))

* Merge pull request #27 from rossumai/mv/add-commitizen-pre-commit

chore: add pre-commit hook for commit messages ([`6bb40da`](https://github.com/rossumai/rossum-sdk/commit/6bb40da3af7c3b2508e7ef295bdb7af257f162c6))


## v0.3.0 (2022-10-17)

### Feature

* feat: add request_json method to ElisAPIClient ([`6c2df87`](https://github.com/rossumai/rossum-sdk/commit/6c2df874934cc5bc2640aeee074cc57cd9cb4faa))

### Unknown

* Merge pull request #26 from rossumai/oh/add-request-json-to-elis-api-client

Add request_json method to ElisAPIClient ([`d59eecd`](https://github.com/rossumai/rossum-sdk/commit/d59eecd80bb447b9c4a6f8198a6845483fd211f5))


## v0.2.0 (2022-10-13)

### Feature

* feat: Implement retrying of failed requests

APIClient now accepts retry configuration where number of retries
and backoff can be configured. ([`09ab473`](https://github.com/rossumai/rossum-sdk/commit/09ab47332fce0c9700107b47ca06d7a1712d653a))

### Unknown

* Merge pull request #25 from rossumai/jo-retry

feat: Implement retrying of failed requests ([`b21e0fb`](https://github.com/rossumai/rossum-sdk/commit/b21e0fbf6edf1e8df4f10ea811d344ab529c1602))


## v0.1.3 (2022-10-12)

### Fix

* fix: change Annotation.confirmed_at type to str instead of datetime ([`40597bb`](https://github.com/rossumai/rossum-sdk/commit/40597bbc937277c04ebdd08d6422df9acfdf9dc7))

### Unknown

* Merge pull request #24 from OndraSlama/ondra-annotation-model-fix

fix: change Annotation.confirmed_at type to str instead of datetime ([`b383edf`](https://github.com/rossumai/rossum-sdk/commit/b383edffe96028c56cb55153e192674f21fe0268))


## v0.1.2 (2022-10-11)

### Fix

* fix: Allow null Organization.trial_expires_at in the model ([`dd95716`](https://github.com/rossumai/rossum-sdk/commit/dd95716f0409c2416cc5637879acd0cdb9aa205f))

### Unknown

* Merge pull request #23 from rossumai/jo-optional-trial-exp

fix: Allow null Organization.trial_expires_at in the model ([`b764a55`](https://github.com/rossumai/rossum-sdk/commit/b764a5522c42596aa7e0b535d8a99df16794fed1))


## v0.1.1 (2022-10-11)

### Fix

* fix: making dependency requirements more relaxed ([`80526da`](https://github.com/rossumai/rossum-sdk/commit/80526da75647be25c7fed581b7a51b337fc98a55))

### Unknown

* Merge pull request #22 from rossumai/miiila/more-relaxed-deps

fix: making dependency requirements more relaxed ([`bfbf70b`](https://github.com/rossumai/rossum-sdk/commit/bfbf70b9ddc9c058363a7b09f09599e4eaf4a5d7))


## v0.1.0 (2022-10-06)

### Chore

* chore: introduce semantic releasing ([`a485874`](https://github.com/rossumai/rossum-sdk/commit/a48587415bb6c197a3d50b91d80f08ace5e8548c))

### Documentation

* docs(readme): add helper page, add makefile ([`1c95bea`](https://github.com/rossumai/rossum-sdk/commit/1c95beac020fc3a88086fddb4979366cd6e3e06f))

### Feature

* feat: first github release by semantic releasing ([`7dd7780`](https://github.com/rossumai/rossum-sdk/commit/7dd77806b030994b00027a17de1895142d852e48))

### Test

* test(api_client): reauth correct exception handling ([`5c0d728`](https://github.com/rossumai/rossum-sdk/commit/5c0d728644fb6a8d1884ce236afdfe9b7ef76bb1))

### Unknown

* Merge pull request #21 from rossumai/mv/introduce-semantic-releasing

Introduce semantic releasing ([`d11fbc5`](https://github.com/rossumai/rossum-sdk/commit/d11fbc5e417be1584339b762613d1dbfbf7298fc))

* Merge pull request #19 from rossumai/oh/return-annotation-id-after-import

Return IDs of created annotations when importing documents ([`048edb4`](https://github.com/rossumai/rossum-sdk/commit/048edb447991be56885dc755df21382d2dff83b4))

* Add support for sideloading resources related to annotation ([`547da3c`](https://github.com/rossumai/rossum-sdk/commit/547da3c437a173256878af764025a9379ba928e9))

* Use dacite library for recursive model loading from JSON

This is very useful when sideloading. As a bonus, we get basic type
validations.

We can also remove our dict_to_dataclass helper since dacite ignores
extra dictionary keys by default. ([`ec8b239`](https://github.com/rossumai/rossum-sdk/commit/ec8b2391a539bfe67ebec03cd084deb8f88bf76d))

* api_client: Allow requesting arbitrary JSONs from full URLs

This is useful for sideloading of additional resources that are
referenced by full URL in the API. ([`34812a2`](https://github.com/rossumai/rossum-sdk/commit/34812a2a2a589e61df499aa0802169e295a3f10a))

* Add method to get organization of currently logged in user ([`7c7a88d`](https://github.com/rossumai/rossum-sdk/commit/7c7a88dd277ff2162750fa7bfdaecf8f0941fc38))

* Return IDs of created annotations when importing documents

This enables the following workflow:

1. Upload a bunch of documents.
2. Poll their status until the documents reach a certain state,
   e.g. `to_review`. ([`875434a`](https://github.com/rossumai/rossum-sdk/commit/875434a7c7ec7ce870cd07b79ae9be25dbcf19ed))

* Merge pull request #20 from rossumai/miiila/remove-unused-sideloading-param

remove unused sideloading parameter ([`5db3f6e`](https://github.com/rossumai/rossum-sdk/commit/5db3f6ec797a9beec51cba79a3db2ed77fd1cc49))

* remove unused sideloading parameter ([`90cce65`](https://github.com/rossumai/rossum-sdk/commit/90cce6555b38cdcae56c21a1d7f81bcc400c0952))

* Merge pull request #18 from rossumai/oh/poll-annotation

elis_api_client: Add poll_annotation method ([`78be140`](https://github.com/rossumai/rossum-sdk/commit/78be1403db01829dcb68c9fcd3c564ad3b350623))

* elis_api_client: Add poll_annotation method

The scenario of uploading a document and waiting until it is processed
is common enough to add it to this general purpose client. ([`1bebcbe`](https://github.com/rossumai/rossum-sdk/commit/1bebcbe48db538c8bd205caa891642efae907648))

* elis_api_client: Rename test methods to match method names ([`2b90a15`](https://github.com/rossumai/rossum-sdk/commit/2b90a1501d3957b82a92dfd99b9c80586c771b72))

* Merge pull request #17 from rossumai/oh/reintroduce-coverage-badge

Re-introduce coverage badge ([`a717028`](https://github.com/rossumai/rossum-sdk/commit/a717028baed4ad6f49a00c6e5e423b3e25e4508f))

* Merge pull request #16 from rossumai/ihe/fix-timeout

Turn off timeout by default ([`9760664`](https://github.com/rossumai/rossum-sdk/commit/976066448d3e472001236b6446404a93755eb1c2))

* Re-introduce coverage badge ([`406116a`](https://github.com/rossumai/rossum-sdk/commit/406116a21977c11ea6ce0bcf6d9443c47bbe7cfe))

* Merge pull request #15 from rossumai/oh/badges

Update badges in README, run codecov after tests ([`4472cdb`](https://github.com/rossumai/rossum-sdk/commit/4472cdb374bb62f37e0ff780c34859911884dfb3))

* Add missing fields to Queue and Annotation ([`2b97d44`](https://github.com/rossumai/rossum-sdk/commit/2b97d448850a0c32b3f705461747d41c33f5bbc6))

* Turn off timeout by default ([`bfa7427`](https://github.com/rossumai/rossum-sdk/commit/bfa7427ffd34921f236d9e54c2cd781eebd4f143))

* Merge pull request #14 from rossumai/add-license

Add LICENCE ([`77b4ccb`](https://github.com/rossumai/rossum-sdk/commit/77b4ccb2742a81633cfcf43b52bc964d1b722c65))

* Update badges in README, run codecov after tests ([`65d41ef`](https://github.com/rossumai/rossum-sdk/commit/65d41efcb33a817a72283063fd2c5d3ebe5b9c09))

* Add LICENCE ([`9b3132d`](https://github.com/rossumai/rossum-sdk/commit/9b3132dffdac6480fa86272ac72851a352f1a75f))

* Merge pull request #12 from rossumai/oh/robust-dataclass-conversion

Drop extra arguments when converting dicts to dataclasses ([`18078d6`](https://github.com/rossumai/rossum-sdk/commit/18078d613018cab4243cfa288937bd60cf2a1f5a))

* Drop extra arguments when converting dicts to dataclasses

...to minimize the need to immediately update the library when a field
is added to an API response. ([`e3f7838`](https://github.com/rossumai/rossum-sdk/commit/e3f78388cca0736693cf731e1b429f2072330167))

* Merge pull request #13 from rossumai/oh/rename-package

Rename rossum_ng package to rossum_api, update README ([`1434772`](https://github.com/rossumai/rossum-sdk/commit/14347729ada67ef236287ef5a768bb3dd6d0a3a1))

* Rename rossum_ng package to rossum_api, update README ([`092ec0b`](https://github.com/rossumai/rossum-sdk/commit/092ec0b6e1622826dc0fc33820f51b5c06cf89de))

* Merge pull request #10 from rossumai/lb/add_only_token_init

add only token init possibility ([`b52305b`](https://github.com/rossumai/rossum-sdk/commit/b52305b911f949cf23376818de77e2217e5a91fa))

* ref(pyproject): delete setup.cfg and move to pyproject.toml ([`44f4ed9`](https://github.com/rossumai/rossum-sdk/commit/44f4ed9068d3a959bba7ac1512f9c76ec7abe63f))

* feat(client) init only with token ([`cb5bdfd`](https://github.com/rossumai/rossum-sdk/commit/cb5bdfd8ffe8917b6ca541fe2706121998dd7cf4))

* Merge pull request #8 from rossumai/mv/implement-sideloading

Implement sideloading ([`8cc68ab`](https://github.com/rossumai/rossum-sdk/commit/8cc68ab1c4e6518bca5d1a6bdbe019107584719b))

* implement sideloading ([`b98b7e1`](https://github.com/rossumai/rossum-sdk/commit/b98b7e127af05ef931358a37bb758ebeffe1a6ed))

* Merge pull request #6 from rossumai/mv/implement-document-export

Add annotation export ([`c60f701`](https://github.com/rossumai/rossum-sdk/commit/c60f70199fa1b4313fcda2a6e3926cd2ddd830a2))

* Merge pull request #9 from rossumai/lbenka-simple-readme

update readme ([`7663223`](https://github.com/rossumai/rossum-sdk/commit/7663223c00b9c2c73a87f283e8bcaa99be2f08d1))

* update readme

providing very simple example at first without confusing parameters ([`337d214`](https://github.com/rossumai/rossum-sdk/commit/337d214dc806e17df6443302f3bff0d2c256582f))

* Merge pull request #7 from rossumai/mv/fix-event-loop-in-jupyter

use existing even_loop if exists ([`7978b53`](https://github.com/rossumai/rossum-sdk/commit/7978b53f759e87302f0456f9eb7e9b9bdebbad89))

* use existing event_loop if exists ([`dccfd3e`](https://github.com/rossumai/rossum-sdk/commit/dccfd3e53614a5eb90a8a3e145a2bfb4d2426371))

* enable e2e test through cron ([`90f3f2b`](https://github.com/rossumai/rossum-sdk/commit/90f3f2be1d9204e2978df6dea3c937d2d9a56cde))

* add annotation export ([`d7d800b`](https://github.com/rossumai/rossum-sdk/commit/d7d800b570b2c57546b098bee9576a796e91295e))

* Merge pull request #5 from rossumai/oh/sideloading

Implement sideloading of related resources in APIClient.fetch_all ([`c990c03`](https://github.com/rossumai/rossum-sdk/commit/c990c03c67d401df8065a7ac97c1bae892ae905e))

* Implement sideloading of related resources in APIClient.fetch_all ([`f2bb57c`](https://github.com/rossumai/rossum-sdk/commit/f2bb57c52e26d7cdb02d7aed3f2899b8cd1a28c1))

* Improve typing of fetch_all and export methods of APIClient

Most of the arguments cannot be generators since the code does not
account for the fact that generators might be exhausted. There is little
benefit of passing these arguments as generators since they are
typically just a few strings. Let&#39;s make the type more strict and use
Sequence. ([`79c0864`](https://github.com/rossumai/rossum-sdk/commit/79c0864e8802d1cbf0cfad8d2f3b54471be303d0))

* Merge pull request #4 from rossumai/mv/complete-e2e-test

more robust E2E test and subsequent methods ([`4f47773`](https://github.com/rossumai/rossum-sdk/commit/4f477734bb2233719f0aae8201179dfccaf885e4))

* more robust E2E test and subsequent methods ([`ef307c0`](https://github.com/rossumai/rossum-sdk/commit/ef307c0345ab599b89dad32f2303305275db5088))

* Merge pull request #3 from rossumai/oh/export-annotations

Add support for the /export endpoint in APIClient ([`4c7eca9`](https://github.com/rossumai/rossum-sdk/commit/4c7eca9d887e1d8446660b761d31b0cad30a800a))

* Add support for export endpoint to APIClient

Unfortunately, authenticate_if_needed decorator must be almost
copypasted to an async generator version. I haven&#39;t found a way to
create an **async** decorator that works both on coroutines and
async generators. ([`0043fb5`](https://github.com/rossumai/rossum-sdk/commit/0043fb59dc36bd0360e89a5280b0696f9b578ce9))

* Use id_ parameter name instead of id in APIClient

The soon-to-be-added export endpoint has a filter with id name which
would cause name clash with the existing parameter. As a bonus, some
IDEs will stop complaining about overriding the built-in id() function. ([`a04ca5e`](https://github.com/rossumai/rossum-sdk/commit/a04ca5ecd55c468c600d07e551552c8c386ba570))

* Refactor APIClient to reduce boilerplate ([`ccc4b0d`](https://github.com/rossumai/rossum-sdk/commit/ccc4b0d6f5b0a360189a78efc671b121189e5f40))

* Merge pull request #1 from rossumai/mv/implement-document-import

Mv/implement document import ([`2beeb55`](https://github.com/rossumai/rossum-sdk/commit/2beeb55a296b6d7327e3cdb639487fe9a9fe856a))

* fix async context manager for aiofiles + e2e tests ([`845080a`](https://github.com/rossumai/rossum-sdk/commit/845080a939b6c28d8e29c986d40e5367d011d016))

* implement import document in both Elis Clients ([`b9d88f8`](https://github.com/rossumai/rossum-sdk/commit/b9d88f8c29892c1fec87f5d05fe86648d2c10a45))

* Correctly type fp argument of APIClient.upload method

...using a type stub from typeshed package. ([`090d93a`](https://github.com/rossumai/rossum-sdk/commit/090d93a611586d3afc6593531c34ff383b3168b8))

* Merge pull request #2 from rossumai/oh/metadata-and-values-in-upload

Allow specifying `metadata` and `values`when uploading files ([`2442633`](https://github.com/rossumai/rossum-sdk/commit/24426336b2e158f8a968389203e5f5d90fc57ef2))

* Repack httpx exceptions to APIClientError

To shield users from the HTTP library we&#39;re using. ([`164998a`](https://github.com/rossumai/rossum-sdk/commit/164998a53b2e968846ecfb653203f2dd03c12c62))

* Allow specifying `metadata` and `values`when uploading files

This led to re-implementing the upload as multi-part file upload which
complicates testing but it is testable with some mocking. ([`a55822b`](https://github.com/rossumai/rossum-sdk/commit/a55822b3390f98d7c93b00e144c3a0e6f7595180))

* Add isort config to pyproject.toml ([`119897f`](https://github.com/rossumai/rossum-sdk/commit/119897f222cfdb994ad143e1bce23ba461571c0f))

* return of the Mock ([`9ac982e`](https://github.com/rossumai/rossum-sdk/commit/9ac982e9c75277f6f1139d20cb2df8a6ccbb5643))

* Implement uploading of document files in APIClient ([`fcb5f34`](https://github.com/rossumai/rossum-sdk/commit/fcb5f34b1577dc35bdb921fcd376109108499334))

* Add README + delete_workspace methods + workspace fixture fix ([`4887516`](https://github.com/rossumai/rossum-sdk/commit/4887516e98925e521fef8577a50672c820a27a0d))

* overcome missing AsyncMock in Python 3.7 and re-nable testing it ([`5476f62`](https://github.com/rossumai/rossum-sdk/commit/5476f62b7dc45282ade0610353fbf21237d7a433))

* move sync client to composition pattern and re-enable mypy ([`907d790`](https://github.com/rossumai/rossum-sdk/commit/907d790010c2417024b29752a8fcb6e5370abd7a))

* fix wrong import of ElisAPIClient ([`db0c93b`](https://github.com/rossumai/rossum-sdk/commit/db0c93be39895b3dd92c19c2faa46cb8f94a1bd4))

* report codecov ([`e5573bc`](https://github.com/rossumai/rossum-sdk/commit/e5573bce5ee9711bb249189419d82b74a88ac13a))

* sync api client ([`01a9f9d`](https://github.com/rossumai/rossum-sdk/commit/01a9f9d60234297b6c749158489ae46efbf9cffa))

* python3.7 - temp. skip ([`c52331b`](https://github.com/rossumai/rossum-sdk/commit/c52331b2013dd7b3b427c01cb9bcf4a41d152093))

* pre-commit setup + linting and typing fixes ([`eff27ee`](https://github.com/rossumai/rossum-sdk/commit/eff27eeaa25ecd2e33666c99fdad33927764ba4d))

* fix type typos ([`e3e8720`](https://github.com/rossumai/rossum-sdk/commit/e3e87203a04020fe2cbd0dc82b4f1ff734fad9dd))

* move testing to travis ([`3ace77c`](https://github.com/rossumai/rossum-sdk/commit/3ace77c2efd6990442352a921ba46eaa3467d325))

* implement all the shared methods ([`2fc4eca`](https://github.com/rossumai/rossum-sdk/commit/2fc4ecad9d1605eb7303906d9dd902847f46d353))

* Implement filtering in APIClient.fetch_all ([`7773406`](https://github.com/rossumai/rossum-sdk/commit/7773406d3240b6b7f7976035f65edee126750698))

* Implement ordering in APIClient ([`64c2e4b`](https://github.com/rossumai/rossum-sdk/commit/64c2e4bc7c6cf949f165ef322e39f4237b829a09))

* first iteration of elis api client ([`c9054a5`](https://github.com/rossumai/rossum-sdk/commit/c9054a55d9004f54552c17bf1042c073467d618d))

* Update test.py to the latest interface of APIClient ([`264cc94`](https://github.com/rossumai/rossum-sdk/commit/264cc9423a060668d51ce2abd7334526df0f9501))

* api_client: Implement properly async pagination ([`aa3ad2e`](https://github.com/rossumai/rossum-sdk/commit/aa3ad2e57a593e7740224da1d123c11c07e6568f))

* Add basic project setup ([`64bbcca`](https://github.com/rossumai/rossum-sdk/commit/64bbcca47db1663ca1c6274d429694412c6e57b3))

* first iteration of elis api client (broken) ([`a597b05`](https://github.com/rossumai/rossum-sdk/commit/a597b05aaea7d6b39b02d22c63280700c1311937))

* fix test + gitignore ([`d05ba8d`](https://github.com/rossumai/rossum-sdk/commit/d05ba8d97b3bdd98686c545351cee7b62bf01ab9))

* Add initial version of APIClient that supports basic CRUD operations ([`342c86a`](https://github.com/rossumai/rossum-sdk/commit/342c86a2875ebae7b908aef7a6e2b990c38824d3))
