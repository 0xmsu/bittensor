# Changelog

## 9.8.2 /2025-07-10

## What's Changed
* edit docstrings by @MichaelTrestman in https://github.com/opentensor/bittensor/pull/2951
* fix and improve e2e stake fee test by @basfroman in https://github.com/opentensor/bittensor/pull/2959
* Make DynamicInfo backwards compatible by @basfroman in https://github.com/opentensor/bittensor/pull/2958
* Update staking fee logic by @basfroman in https://github.com/opentensor/bittensor/pull/2961

## New Contributors
* @MichaelTrestman made their first contribution in https://github.com/opentensor/bittensor/pull/2951

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.8.1...v9.8.2

## 9.8.1 /2025-07-08

## What's Changed
* New logic to get price for `DynamicInfo` by @basfroman in https://github.com/opentensor/bittensor/pull/2952
* Update to safe_staking limits by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2950

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.8.0...v9.8.1

## 9.8.0 /2025-07-07

## What's Changed
* Update e2e-tests (metagraph_info, staking) by @basfroman in https://github.com/opentensor/bittensor/pull/2907
* Add method to fetch parents for child hotkeys by @thewhaleking in https://github.com/opentensor/bittensor/pull/2906
* Add local env variable for `config.wallet.*` by @basfroman in https://github.com/opentensor/bittensor/pull/2908
* Subtensor docstring cleanup by @thewhaleking in https://github.com/opentensor/bittensor/pull/2910
* chore(ci): upgrade Docker GitHub Actions to latest stable versions by @MamunC0der in https://github.com/opentensor/bittensor/pull/2912
* improve `scripts/install.sh` by @basfroman in https://github.com/opentensor/bittensor/pull/2914
* Cleanup websocket integration data by @thewhaleking in https://github.com/opentensor/bittensor/pull/2915
* chore: fix some typos in comment by @eveneast in https://github.com/opentensor/bittensor/pull/2868
* Add `SKIP_PULL` variable for conftest.py by @basfroman in https://github.com/opentensor/bittensor/pull/2920
* Update `SubnetIdentity` with subtensor related v3 changes by @basfroman in https://github.com/opentensor/bittensor/pull/2923
* add time for flaky test by @basfroman in https://github.com/opentensor/bittensor/pull/2924
* Add `root_set_pending_childkey_cooldown_extrinsic` by @basfroman in https://github.com/opentensor/bittensor/pull/2925
* New logic for alpha low and high (0.025 <= alpha_low <= alpha_high <= 1) by @basfroman in https://github.com/opentensor/bittensor/pull/2927
* Fix Typo in test_commit_weights.py by @zeevick10 in https://github.com/opentensor/bittensor/pull/2922
* New websockets option by @thewhaleking in https://github.com/opentensor/bittensor/pull/2917
* Retry archive node support by @thewhaleking in https://github.com/opentensor/bittensor/pull/2909
* Fix: Safe staking e2e test by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2929
* fix type conversion in axon preprocess by @Windfarer in https://github.com/opentensor/bittensor/pull/2930
* [LINT] Improved type hints by @Arthurdw in https://github.com/opentensor/bittensor/pull/2918
* Set balance netuids in staking tests by @thewhaleking in https://github.com/opentensor/bittensor/pull/2934
* Improve subnet method logic by @basfroman in https://github.com/opentensor/bittensor/pull/2937
* Update `SubnetHyperparameters` with v2 by @basfroman in https://github.com/opentensor/bittensor/pull/2938
* upgrade numpy by @thewhaleking in https://github.com/opentensor/bittensor/pull/2936
* decode metadata with empty value by @thewhaleking in https://github.com/opentensor/bittensor/pull/2940
* Reset bonds by @andreea-popescu-reef in https://github.com/opentensor/bittensor/pull/2876
* Add new logic for `unstake_all` extrinsics by @basfroman in https://github.com/opentensor/bittensor/pull/2897
* SelectiveMetagraph back by @basfroman in https://github.com/opentensor/bittensor/pull/2887
* add unstake_all to SubtensorApi.extrinsics by @basfroman in https://github.com/opentensor/bittensor/pull/2943
* Integrate Liquidity Provider feature by @basfroman in https://github.com/opentensor/bittensor/pull/2939
* Fix e2e test metagraph after chain change by @basfroman in https://github.com/opentensor/bittensor/pull/2945

## New Contributors
* @MamunC0der made their first contribution in https://github.com/opentensor/bittensor/pull/2912
* @eveneast made their first contribution in https://github.com/opentensor/bittensor/pull/2868
* @Windfarer made their first contribution in https://github.com/opentensor/bittensor/pull/2930

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.7.0...v9.8.0

## 9.7.1 /2025-06-06

## What's Changed
* Update e2e-tests (metagraph_info, staking) by @basfroman in https://github.com/opentensor/bittensor/pull/2907

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.7.0...v9.7.1

## 9.7.0 /2025-05-29

## What's Changed
* Add `get_subnet_info` by @basfroman in https://github.com/opentensor/bittensor/pull/2894
* Fix bug in `get_next_epoch_start_block` by @basfroman in https://github.com/opentensor/bittensor/pull/2899
* e2e workflow: improve skipping logic (no error when skip the job) by @basfroman in https://github.com/opentensor/bittensor/pull/2898
* Replace `transfer_allow_death` with `transfer_keep_alive` by @basfroman in https://github.com/opentensor/bittensor/pull/2900
* Fix broken pull request template links (#2867) by @AgSpades in https://github.com/opentensor/bittensor/pull/2883
* update pr templates with branch ack by @thewhaleking in https://github.com/opentensor/bittensor/pull/2903

## New Contributors
* @AgSpades made their first contribution in https://github.com/opentensor/bittensor/pull/2883

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.6.1...v9.7.0

## 9.6.1 /2025-05-22

## What's Changed
* Release/9.6.0 by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2882
* Add stake before check `validator_permit` by @basfroman in https://github.com/opentensor/bittensor/pull/2884
* Add defaults for endpoint and network from local env by @basfroman in https://github.com/opentensor/bittensor/pull/2886
* Improve error message by @basfroman in https://github.com/opentensor/bittensor/pull/2888
* Make `unstake` and `unstake_multiple` for all Alphas more clear by @basfroman in https://github.com/opentensor/bittensor/pull/2885
* fix publish metadata by @basfroman in https://github.com/opentensor/bittensor/pull/2890

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.6.0...v9.6.1

## 9.6.0 /2025-05-15

* Add manual way to show the size of virtual environments in the PR by @basfroman in https://github.com/opentensor/bittensor/pull/2875
* Improve `Monitor SDK Requirements Size` workflow by @basfroman in https://github.com/opentensor/bittensor/pull/2878
* Add subtensor.is_subnet_active method by @basfroman in https://github.com/opentensor/bittensor/pull/2877
* Using `hotkey` instead of `coldkey` to sign extrinsic in `serve_axon` by @basfroman in https://github.com/opentensor/bittensor/pull/2879
* Rename argument `fallback_chains` to `fallback_endpoints` by @basfroman in https://github.com/opentensor/bittensor/pull/2880

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.5.0...v9.6.0

## 9.5.0 /2025-05-12

## What's Changed
* Release/9.4.0 by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2837
* Update subnet units by @thewhaleking in https://github.com/opentensor/bittensor/pull/2838
* Add `force_register_neuron` into MockSubtensor by @basfroman in https://github.com/opentensor/bittensor/pull/2839
* Add `Monitor-Requirements-Size` workflow by @basfroman in https://github.com/opentensor/bittensor/pull/2842
* Add `SelectiveMetagraph` interface into SDK by @basfroman in https://github.com/opentensor/bittensor/pull/2846
* Update docs for unstake amount by @thewhaleking in https://github.com/opentensor/bittensor/pull/2845
* Add one more attempt to e2e tests by @basfroman in https://github.com/opentensor/bittensor/pull/2849
* Fix typos in test documentation and docstrings by @leopardracer in https://github.com/opentensor/bittensor/pull/2848
* Add bittensor-drand==0.5.0 by @basfroman in https://github.com/opentensor/bittensor/pull/2835
* Extend selective metagraph logic by @basfroman in https://github.com/opentensor/bittensor/pull/2852
* fix: $BASH_ENV loading issue by @defitricks in https://github.com/opentensor/bittensor/pull/2851
* Update github actions versions due to deprecation by @PixelPil0t1 in https://github.com/opentensor/bittensor/pull/2850
* Add methods to Async/Subtensor class by @basfroman in https://github.com/opentensor/bittensor/pull/2854
* Cleanup, refactoring, small fix, improvement by @basfroman in https://github.com/opentensor/bittensor/pull/2856
* Add `period` argument to extrinsics calls by @basfroman in https://github.com/opentensor/bittensor/pull/2857
* Add nightly run of e2e tests by @basfroman in https://github.com/opentensor/bittensor/pull/2858
* `period=16` for fast blocks test by @basfroman in https://github.com/opentensor/bittensor/pull/2859
* Fix some unittests warnings by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2774
* docs: fix typos in  `README.md` by @gap-editor in https://github.com/opentensor/bittensor/pull/2861
* Introduce `SubtensorApi` interface for SDK by @basfroman in https://github.com/opentensor/bittensor/pull/2862
* Adds `__all__` to easy_imports.py to get rid of all the #noqa stuff by @thewhaleking in https://github.com/opentensor/bittensor/pull/2863
* `🥩s` to `staking` by @basfroman in https://github.com/opentensor/bittensor/pull/2864
* Fix `get_next_epoch_start_block` by @basfroman in https://github.com/opentensor/bittensor/pull/2865
* docs: fix dead link by @GarmashAlex in https://github.com/opentensor/bittensor/pull/2866
* Add `non-fast-blocks` e2e tests each Saturday by @basfroman in https://github.com/opentensor/bittensor/pull/2860
* Selective-metagraph -> MetagraphInfo by @basfroman in https://github.com/opentensor/bittensor/pull/2870
* Improve e2e tests and fix bug in SubtensorApi by @basfroman in https://github.com/opentensor/bittensor/pull/2869

## New Contributors
* @defitricks made their first contribution in https://github.com/opentensor/bittensor/pull/2851
* @PixelPil0t1 made their first contribution in https://github.com/opentensor/bittensor/pull/2850
* @gap-editor made their first contribution in https://github.com/opentensor/bittensor/pull/2861
* @GarmashAlex made their first contribution in https://github.com/opentensor/bittensor/pull/2866

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.4.0...v9.5.0

## 9.4.0 /2025-04-17

## What's Changed
* Release/9.3.0 by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2805
* Fix for flaky behavior of `test_incentive`, `test_commit_weights` and `test_set_weights`  by @basfroman in https://github.com/opentensor/bittensor/pull/2795
* Add `get_next_epoch_start_block` method to Async/Subtensor by @basfroman in https://github.com/opentensor/bittensor/pull/2808
* Adds compatibility for torch 2.6.0+ by @thewhaleking in https://github.com/opentensor/bittensor/pull/2811
* f Update CONTRIBUTING.md by @Hack666r in https://github.com/opentensor/bittensor/pull/2813
* docs: replaced discord link with documentation by @sashaphmn in https://github.com/opentensor/bittensor/pull/2809
* sometimes it's still flaky because the chain returns data with time offset by @basfroman in https://github.com/opentensor/bittensor/pull/2816
* Remove requirements directory by @thewhaleking in https://github.com/opentensor/bittensor/pull/2812
* version in one place by @thewhaleking in https://github.com/opentensor/bittensor/pull/2806
* Update CONTRIBUTING hyperlinks by @thewhaleking in https://github.com/opentensor/bittensor/pull/2820
* 9.3.1a1: Updates changelog by @ibraheem-abe in https://github.com/opentensor/bittensor/pull/2821
* Remove cubit as extra by @thewhaleking in https://github.com/opentensor/bittensor/pull/2823
* fix/roman/get-metagraph-identities by @basfroman in https://github.com/opentensor/bittensor/pull/2826
* Replace waiting logic for `test_commit_reveal_v3.py` by @basfroman in https://github.com/opentensor/bittensor/pull/2827
* Add `start_call` extrinsic to the sdk by @basfroman in https://github.com/opentensor/bittensor/pull/2828
* Add `timelock` module by @basfroman in https://github.com/opentensor/bittensor/pull/2824
* Fix: raise_error=True in AsyncSubtensor fails to get error_message by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2771
* Fix: async set_subnet_identity_extrinsic doesn't sign the extrinsic by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2772
* Update settings.py by @petryshkaCODE in https://github.com/opentensor/bittensor/pull/2814
* Bumping ruff version by @basfroman in https://github.com/opentensor/bittensor/pull/2831
* Fix and improve e2e tests after `start call` new limit in subtensor by @basfroman in https://github.com/opentensor/bittensor/pull/2830
* Add `bittensor.timelock` module description by @basfroman in https://github.com/opentensor/bittensor/pull/2833
* fix: Update broken link in `CONTRIBUTING.md` by @cypherpepe in https://github.com/opentensor/bittensor/pull/2818
* docs: added a new badge by @sashaphmn in https://github.com/opentensor/bittensor/pull/2819
* Fix AxonInfo initialization in get_mock_neuron function by @VolodymyrBg in https://github.com/opentensor/bittensor/pull/2803
* Dendrite: log ClientOSError as Debug by @Thykof in https://github.com/opentensor/bittensor/pull/2770
* remove `rao` endpoint from settings by @basfroman in https://github.com/opentensor/bittensor/pull/2834

## New Contributors
* @Hack666r made their first contribution in https://github.com/opentensor/bittensor/pull/2813
* @petryshkaCODE made their first contribution in https://github.com/opentensor/bittensor/pull/2814
* @cypherpepe made their first contribution in https://github.com/opentensor/bittensor/pull/2818
* @VolodymyrBg made their first contribution in https://github.com/opentensor/bittensor/pull/2803
* @Thykof made their first contribution in https://github.com/opentensor/bittensor/pull/2770

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.3.0...v9.4.0

## 9.3.0 /2025-04-09

## What's Changed
* More E2E tests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2754
* Fix E2E: fix wait_epoch and next_tempo by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2753
* Add all supported python versions to e2e tests workflow by @basfroman in https://github.com/opentensor/bittensor/pull/2761
* update docker image name by @basfroman in https://github.com/opentensor/bittensor/pull/2760
* Add pypi package version checker for `python -m bittensor` by @basfroman in https://github.com/opentensor/bittensor/pull/2762
* Feat: set_children and get_pending_children methods by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2752
* Add logic for keep docker image up to date by @basfroman in https://github.com/opentensor/bittensor/pull/2765
* Fix: CI/CD Set up Python version for E2E tests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2767
* Fix E2E Tests: wait for new nonce by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2768
* Fix e2e `conftest.py` for legacy runner by @basfroman in https://github.com/opentensor/bittensor/pull/2769
* Fix E2E with devnet-ready by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2776
* Add compatibility check for 3.13 by @thewhaleking in https://github.com/opentensor/bittensor/pull/2779
* Fix E2E test_dendrite by making sure Alice is Top validator in Subnet by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2780
* Add get_owned_hotkeys to subtensor and async one + tests by @basfroman in https://github.com/opentensor/bittensor/pull/2766
* Add drand-commitments by @basfroman in https://github.com/opentensor/bittensor/pull/2781
* Missing f-string format by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2785
* bump version by @basfroman in https://github.com/opentensor/bittensor/pull/2786
* Improvement and fix for https://github.com/opentensor/bittensor/pull/2781 by @basfroman in https://github.com/opentensor/bittensor/pull/2787
* Add `stop_existing_test_containers` logic before run e2e test/s by @basfroman in https://github.com/opentensor/bittensor/pull/2790
* Bump async substrate interface by @thewhaleking in https://github.com/opentensor/bittensor/pull/2788
* Improve CRv3 functionality  by @basfroman in https://github.com/opentensor/bittensor/pull/2791
* Improve logic in Balance magic methods by @basfroman in https://github.com/opentensor/bittensor/pull/2764
* Requirements update by @thewhaleking in https://github.com/opentensor/bittensor/pull/2789
* remove Levenshtein requirement by @thewhaleking in https://github.com/opentensor/bittensor/pull/2802

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.2.0...v9.3.0

## 9.2.0 /2025-03-18

## What's Changed
* Fix E2E test_incentive by waiting till start of the very next epoch by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2746
* New era of e2e Tests Bittensor by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2743
* Allow installation on Py 3.13 by @thewhaleking in https://github.com/opentensor/bittensor/pull/2756
* Feat/dynamic stake prices by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2755

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.1.0...v9.2.0

## 9.1.0 /2025-03-12

## What's Changed
* Refactor duplicated unittests code by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2724
* Use uv for circleci by @thewhaleking in https://github.com/opentensor/bittensor/pull/2729
* Fix E2E test_metagraph_info by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2728
* Tests: deduplicate fake_wallet and correctly create Mock by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2730
* E2E Test: wait cooldown period to check set_children effect by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2733
* Tests: wait for Miner/Validator to fully start by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2737
* All metagraph subtensor methods now use block by @thewhaleking in https://github.com/opentensor/bittensor/pull/2738
* Tests: increse test_incentive timeout + fix sudo_set_weights_set_rate_limit by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2739
* Feat/safe staking by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2736
* 9.0.5: Bumps version and changelog by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2741
* Tests: enable E2E test_batch_operations by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2744
* Fix: burned_register supports root subnet (netuid=0 param) by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2732
* Feat: set_delegate_take by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2731
* Renames rate_threshold -> rate_tolerance by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2745

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.4...v9.1.0

## 9.0.4 /2025-03-06

## What's Changed
* Release/9.0.3 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2712
* improve `wait_for_node_start` until 20 mins by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2714
* More E2E tests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2678
* fix(2715): use ChainIdentity for identities by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2718
* Metagraph use block correctly in `_get_all_stakes_from_chain` by @thewhaleking in https://github.com/opentensor/bittensor/pull/2719
* Integration tests for async-substrate-interface 1.0.4 compatibility by @thewhaleking in https://github.com/opentensor/bittensor/pull/2720
* Backmerge main staging 904 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2721
* Skip E2E test_children by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2723
* More Subtensor unnitests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2713
* Change to pyproject.toml by @thewhaleking in https://github.com/opentensor/bittensor/pull/2504
* Updates test_incentive by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2722
* Use uv for gh actions  by @thewhaleking in https://github.com/opentensor/bittensor/pull/2503
* Bumps async substrate interface by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2725

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.3...v9.0.4

## 9.0.3 /2025-02-26

## What's Changed
* Release/9.0.2 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2696
* fix: typos in config test by @EricHasegawa in https://github.com/opentensor/bittensor/pull/2693
* Removes limits in async + unstake_multiple by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2701
* Fixes get_all_commitments, adds tests. by @thewhaleking in https://github.com/opentensor/bittensor/pull/2699
* Use `.value` in e2e test by @thewhaleking in https://github.com/opentensor/bittensor/pull/2700
* Fix e2e test setup by @thewhaleking in https://github.com/opentensor/bittensor/pull/2681
* Dendrite `__del__` method fix by @thewhaleking in https://github.com/opentensor/bittensor/pull/2702
* Fix E2E test_set_weights by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2703
* Updates test incentive by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2688
* Add `get_timestamp` method by @thewhaleking in https://github.com/opentensor/bittensor/pull/2704
* fix: async get_delegated by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2706
* Properly mock data_chain class methods by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2705
* Install btcli from install sh by @thewhaleking in https://github.com/opentensor/bittensor/pull/2708
* Bumps dependencies of async substrate + btwallet by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2710
* Backmerge/main to staging 902 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2711

## New Contributors
* @EricHasegawa made their first contribution in https://github.com/opentensor/bittensor/pull/2693

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.2...v9.0.3

## 9.0.2 /2025-02-24

## What's Changed
* CI: Upgrade rust compiler for E2E tests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2690
* Break away cli reqs by @thewhaleking in https://github.com/opentensor/bittensor/pull/2692
* Updates DelegateInfo chain data by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2683
* Backmerge main to staging 901 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2689
* fix: typos in documentation files by @zeevick10 in https://github.com/opentensor/bittensor/pull/2687
* Removes tx limit in stake_multiple by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2694

## New Contributors
* @zeevick10 made their first contribution in https://github.com/opentensor/bittensor/pull/2687

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.1...v9.0.2

## 9.0.1 /2025-02-20

## What's Changed
* Release/9.0.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2671
* fix e2e test by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2673
* fix e2e test incentive by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2674
* Add compatibility for read-only systems by @Arthurdw in https://github.com/opentensor/bittensor/pull/2676
* test: use asynccontextmanager for FastAPI lifespan by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2597
* test(2472): offline unittests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2596
* Removes redundant assignments in Metagraph by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2680
* Alpha str formatting by @thewhaleking in https://github.com/opentensor/bittensor/pull/2672
* Add method for fetching all Neuron Certificates on a Netuid by @thewhaleking in https://github.com/opentensor/bittensor/pull/2677
* Updates tao_stake in MetagraphInfo by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2682
* fix(2188): configure uvicorn event loop by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2679
* Refactor AsyncSubtensor aenter logic by @thewhaleking in https://github.com/opentensor/bittensor/pull/2684
* Backmerge master to staging 900 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2685

## New Contributors
* @Arthurdw made their first contribution in https://github.com/opentensor/bittensor/pull/2676

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0...v9.0.1

## 9.0.0 /2025-02-13

## What's Changed
* Optimisations and tests for Async Sync Subtensor by @thewhaleking in https://github.com/opentensor/bittensor/pull/2569
* [SDK] Get rid of py-substrate-interface (DO NOT MERGE) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2565
* Uses the new async_substrate_interface lib by @thewhaleking in https://github.com/opentensor/bittensor/pull/2572
* AsyncSubstrateInterface Overhaul (with Sync AsyncSubstrate) by @thewhaleking in https://github.com/opentensor/bittensor/pull/2526
* [SDK] Small improvements by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2575
* Sync Subtensor warning by @thewhaleking in https://github.com/opentensor/bittensor/pull/2578
* [SDK] Fixes types in async by @thewhaleking in https://github.com/opentensor/bittensor/pull/2577
* Release/8.5.2 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2584
* fix: typos in documentation files by @leopardracer in https://github.com/opentensor/bittensor/pull/2580
* fix(2337): btlogging setLevel by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2588
* perf: don't use 2 threads to create FastAPI server by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2592
* fix(2188): don't allow uvicorn to reconfigure event_loop_policy by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2591
* Fix spelling errors by @Dimitrolito in https://github.com/opentensor/bittensor/pull/2586
* Make code as beautiful as it has never been before by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2599
* test: bring back old (sync subtensor) tests and fix them by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2600
* YAASO: Yet Another AsyncSubtensor Overhaul by @thewhaleking in https://github.com/opentensor/bittensor/pull/2579
* Add alias for `Subtensor.commit` as `set_commitment` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2606
* [RAO] Add methods to fetch metagraph data from the chain by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2605
* Rewrite config.py by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2607
* Update metagraph class with `rao` stuff by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2611
* [RAO] fix for unit test + refactoring by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2612
* fix integration metagraph test by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2613
* Cleanups, fixes, improvements for rao by @thewhaleking in https://github.com/opentensor/bittensor/pull/2614
* Adds deprecation notice for non-balance amounts by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2615
* Staging pre merge port rao (New async substrate) by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2610
* Tests for SyncSubtensor by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2617
* Many small fixes by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2619
* Use async-substrate-interface for runtime decoding by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2618
* Pins torch version to 2.5.1 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2623
* Fixes, adds stake and other methods by @thewhaleking in https://github.com/opentensor/bittensor/pull/2622
* Fix typos by @Marcofann in https://github.com/opentensor/bittensor/pull/2620
* Add `subnet_volume` field to `MetagraphInfo` and `DynamicInfo` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2624
* Update wallet creation command logs post-install by @HudsonGraeme in https://github.com/opentensor/bittensor/pull/2621
* fix subtensor methods for async by @thewhaleking in https://github.com/opentensor/bittensor/pull/2628
* Subnet burn cost return type by @thewhaleking in https://github.com/opentensor/bittensor/pull/2629
* Specifies a range of torch versions, rather than a pinned version. by @thewhaleking in https://github.com/opentensor/bittensor/pull/2632
* Adds subnet registration extrinsic by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2630
* Bumps btwallet 302 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2633
* SKD implementation for Subtensor `Feat/RPC Upgrades`. PR #1205 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2627
* Bug fixes after release SDK v9.0.0rc1 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2637
* Adds Latent Lite endpoint to the SDK by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2641
* Bringing meta fields to a common form with float values float(TAO) instead of Balance and Tensor by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2642
* Adds `get_all_commitments` and fixes commitment tests and `query_map` by @thewhaleking in https://github.com/opentensor/bittensor/pull/2644
* Fix for extra fields from chain data by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2647
* Fix InfoBase + dataclasses by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2649
* fix integration tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2651
* feat: Add logging for unexpected header keys in Synapse by @crStiv in https://github.com/opentensor/bittensor/pull/2587
* Fixes Dendrite new loop close by @thewhaleking in https://github.com/opentensor/bittensor/pull/2654
* Fix e2e tests by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2639
* feat/roman/deps by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2655
* Metagraph Improvements by @thewhaleking in https://github.com/opentensor/bittensor/pull/2659
* add name and symbol fields to metagraph by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2658
* Using one determine_chain_endpoint_and_network by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2661
* Tests: separate `templates` fixture by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2660
* Merge `async-pre-merge-new-async` to `staging` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2656
* Add `set_subnet_identity_extrinsic` and related stuff by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2662
* Changes the logging level for unexpected header keys to trace by @thewhaleking in https://github.com/opentensor/bittensor/pull/2666
* Remove logs by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2667
* Tests: properly handle subprocesses (subtensor, miner, validator) by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2664
* Last-minute requests by @thewhaleking in https://github.com/opentensor/bittensor/pull/2665
* Updates tao_weights for mainnet by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2669
* Update deps and default network/endpoint by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2670

## New Contributors
* @leopardracer made their first contribution in https://github.com/opentensor/bittensor/pull/2580
* @Dimitrolito made their first contribution in https://github.com/opentensor/bittensor/pull/2586
* @Marcofann made their first contribution in https://github.com/opentensor/bittensor/pull/2620
* @HudsonGraeme made their first contribution in https://github.com/opentensor/bittensor/pull/2621
* @crStiv made their first contribution in https://github.com/opentensor/bittensor/pull/2587

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.5.2...v9.0.0

## 9.0.0rc6 /2025-02-11
* Using one determine_chain_endpoint_and_network by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2661
* Tests: separate templates fixture by @zyzniewski-reef  in https://github.com/opentensor/bittensor/pull/2660
* add name and symbol fields to metagraph by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2658
* Metagraph Improvements by @thewhaleking in https://github.com/opentensor/bittensor/pull/2659
* feat/roman/add-subnet-identity-with-subnet-creation by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2662

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0rc5...v9.0.0rc6

## 9.0.0rc5 /2025-02-07
* Fix InfoBase + dataclasses @roman-opentensor in https://github.com/opentensor/bittensor/pull/2649

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0rc4...v9.0.0rc5

## 9.0.0rc4 /2025-02-07
* Fix for extra fields from chain data by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2647
* Adds get_all_commitments and fixes commitment tests and query_map @thewhaleking in https://github.com/opentensor/bittensor/pull/2644

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0rc2...v9.0.0rc3

## 9.0.0rc3 /2025-02-06

## What's Changed
* Adds methods to better accommodate the new websocket implementation (long-lived) by @thewhaleking in https://github.com/opentensor/bittensor/commit/3c44be177edef8a799c2c9dc5e49916723cab5c2
* Adds latent-lite network by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2641
* Updates async-substrate-interface to 1.0.0rc12 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/commit/9d0b008e6163c84ed9267423324f30c3ec8af289
* Bringing meta fields to a common form with float values float(TAO) instead of Balance and Tensor by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2642

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0rc2...v9.0.0rc3

## 9.0.0rc2 /2025-02-05

## What's Changed
* Small bug fixes and improvements by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2637

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v9.0.0rc1...v9.0.0rc2

## 9.0.0rc1 /2025-02-05

## What's Changed
* Uses revamped Async Substrate Interface
* Compatibility with Rao changes added
* Completely revamped Async Subtensor introduced
* Numerous improvements, bug fixes, and deprecations

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.5.1...v9.0.0rc1

## 8.5.2 /2025-01-17

## What's Changed
* Feat/use tx pool for set weights by @camfairchild in https://github.com/opentensor/bittensor/pull/2534
* fix get_delegates result decoding by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2551
* [SDK] Handle server connection limit  by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2553
* Backmerge master to staging post 851 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2557
* [SDK] Improve InvalidStatus handler by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2558
* [SDK] Add async version of commit reveal v3 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2560
* Use apt-get instead of apt for scripts by @camfairchild in https://github.com/opentensor/bittensor/pull/2571
* fix _do_stake incorrect arguments error in staking.py by @Assh-codes in https://github.com/opentensor/bittensor/pull/2574
* Updates tests for btwallet 3.0.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2540
* Bumps cr3 FFI by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2583

## New Contributors
* @Assh-codes made their first contribution in https://github.com/opentensor/bittensor/pull/2574

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.5.1...v8.5.2

## 8.5.1 /2024-12-16

## What's Changed
* 8.5.0 bugfixes by @thewhaleking in https://github.com/opentensor/bittensor/pull/2541
* Removes substrate call in format_error_message by @thewhaleking in https://github.com/opentensor/bittensor/pull/2542
* Remove torch from the weights calls by @thewhaleking in https://github.com/opentensor/bittensor/pull/2543
* optional arg fix by @thewhaleking in https://github.com/opentensor/bittensor/pull/2544
* async cr3 not implemented by @thewhaleking in https://github.com/opentensor/bittensor/pull/2545
* Backmerge master to staging 851 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2546
* Adds retry in CRv3 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2547

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.5.0...v8.5.1

## 8.5.0 /2024-12-12

## What's Changed
* add improved reveal-round params by @JohnReedV in https://github.com/opentensor/bittensor/pull/2509
* fix: add default value to the get_block_number method in AsyncSubstrateInterface by @FLiotta in https://github.com/opentensor/bittensor/pull/2529
* Mismatched "archive" index by @thewhaleking in https://github.com/opentensor/bittensor/pull/2530
* Adds a factory function to create an initialised AsyncSubtensor object. by @thewhaleking in https://github.com/opentensor/bittensor/pull/2516
* chore: fix some comments by @lvyaoting in https://github.com/opentensor/bittensor/pull/2515
* Fixes E2E test chain buffer issues on devnet by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2531
* Added e2e test for CRv3 + enhancements by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2532
* Backmerge master to staging 850 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2535
* Enhancement/adds total stake functions by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2537
* Fixes get_current_block by @thewhaleking in https://github.com/opentensor/bittensor/pull/2536
* [SDK] Add `commit reveal v3` logic (python part only) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2484

## New Contributors
* @JohnReedV made their first contribution in https://github.com/opentensor/bittensor/pull/2509
* @FLiotta made their first contribution in https://github.com/opentensor/bittensor/pull/2529
* @lvyaoting made their first contribution in https://github.com/opentensor/bittensor/pull/2515

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.5...v8.5.0

## 8.4.5 /2024-12-05

## What's Changed
* Overrides copy and deep copy for the metagraph by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2523

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.4...v8.4.5

## 8.4.4 /2024-12-05

## What's Changed
* Removes the call that automatically sets everything to warning level debugging by @thewhaleking in https://github.com/opentensor/bittensor/pull/2508
* Exit `set_weights` on success by @thewhaleking in https://github.com/opentensor/bittensor/pull/2511
* `test_dendrite` test clean up by @thewhaleking in https://github.com/opentensor/bittensor/pull/2512
* Adds --logging.info level so it can be set @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2510
* Allows wallet to be created through configs in the axon if it is provided by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2510
* Changes verbosity level of ClientConnectorError and TimeoutError in the dendrite to debug by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2510
* Fixes behaviour of config initialization for axon, subtensor, logging and threadpool by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2510
* metagraph sync fix by @thewhaleking in https://github.com/opentensor/bittensor/pull/2514
* Remove metadata retrieval of custom errors from format_error_message by @thewhaleking in https://github.com/opentensor/bittensor/pull/2518
* Backmerge master to staging for 8.4.4 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2519
* Updates bt-decode to 0.4.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2520

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.3...v8.4.4

## 8.4.3 /2024-12-02

## What's Changed

* Fix logging config parsing by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2500
* Improve  `submit_extrinsic` util by @thewhaleking in https://github.com/opentensor/bittensor/pull/2502
* Backmerge master to staging for 843 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2505
* WS ensure_connected socket catch by @thewhaleking in https://github.com/opentensor/bittensor/pull/2507

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.2...v8.4.3

## 8.4.2 /2024-11-28

## What's Changed

* Fix submit_extrinsic timeout by @thewhaleking in https://github.com/opentensor/bittensor/pull/2497
* Backmerge master to staging for 841 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2498

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.1...v8.4.2

## 8.4.1 /2024-11-27

## What's Changed

* Backmerge master 840 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2494
* Enable arguments to be set in axon config by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2493

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.4.0...v8.4.1

## 8.4.0 /2024-11-27

## What's Changed

* Async unittests for `bittensor/core/extrinsics/async_weights.py` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2425
* Async unittests for `bittensor/core/extrinsics/async_transfer.py` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2426
* Async `unittests for bittensor/core/extrinsics/async_root.py` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2427
* Removes Conda Info by @thewhaleking in https://github.com/opentensor/bittensor/pull/2437
* Fix typos by @omahs in https://github.com/opentensor/bittensor/pull/2440
* [SDK] Registration related content refactoring by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2439
* Async unittests for `bittensor/core/extrinsics/async_registration.py` by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2445
* BittensorConsole class by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2446
* Improve reconnection logic by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2442
* E2E tests - Increasing Subtensor coverage (Pt 1) by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2443
* Add python3.12 support by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2450
* add neuron certificate discovery by @andreea-popescu-reef in https://github.com/opentensor/bittensor/pull/2267
* Use websockets for Subtensor by @thewhaleking in https://github.com/opentensor/bittensor/pull/2455
* Part 2: E2E tests - Increasing Subtensor coverage by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2457
* Tests for subtensor methods related with `stake` and `unstake` extrinsics by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2458
* Apply BittensorConsole + logging refactoring by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2452
* Add staking and unstaking extrinsics by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2456
* Don't strip ANSI from stdout (fixes #2365) by @vaqxai in https://github.com/opentensor/bittensor/pull/2366
* Support fastblocks when setting root set weights in e2e tests by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2464
* Extrinsic Submission Timeout by @thewhaleking in https://github.com/opentensor/bittensor/pull/2448
* Resync async substrate by @thewhaleking in https://github.com/opentensor/bittensor/pull/2463
* Fixes logging when setting weights by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2465
* Integration tests by @thewhaleking in https://github.com/opentensor/bittensor/pull/2433
* Fixes logic for checking block_since_last_update by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2473
* Update unit tests websocket by @thewhaleking in https://github.com/opentensor/bittensor/pull/2468
* Improve MockSubtensor by @thewhaleking in https://github.com/opentensor/bittensor/pull/2469
* Fixes logging when passing multiple objects by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2477
* Add script for solving ssl issue by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2474
* Improve async docstrings by @thewhaleking in https://github.com/opentensor/bittensor/pull/2478
* fix: increase stacklevel in LoggingMachine log calls by @zyzniewski-reef in https://github.com/opentensor/bittensor/pull/2476
* remove uses of return scale obj by @thewhaleking in https://github.com/opentensor/bittensor/pull/2479
* Backmerge master to staging for 8.4.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2482
* Expand `reuse_block` by @thewhaleking in https://github.com/opentensor/bittensor/pull/2481
* Add NeuronInfo list from vec u8 by @camfairchild in https://github.com/opentensor/bittensor/pull/2480
* Update `ensure_connected` for websockets by @thewhaleking in https://github.com/opentensor/bittensor/pull/2486
* MockSubtensor work offline by @thewhaleking in https://github.com/opentensor/bittensor/pull/2487
* Add `wait_for_block` method by @thewhaleking in https://github.com/opentensor/bittensor/pull/2489
* Updates btwallet to 2.1.2 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2490
* Bumps bittensor wallet to 2.1.3 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2492

## New Contributors
* @vaqxai made their first contribution in https://github.com/opentensor/bittensor/pull/2366
* @zyzniewski-reef made their first contribution in https://github.com/opentensor/bittensor/pull/2476

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.3.1...v8.4.0

## 8.3.1 /2024-11-14

## What's Changed
* Fixes broken Subtensor methods by @thewhaleking in https://github.com/opentensor/bittensor/pull/2420
* [Tests] AsyncSubtensor (Part 7: The final race) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2418

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.3.0...v8.3.1

## 8.3.0 /2024-11-13

## What's Changed
* Expands the type registry to include all the available options by @thewhaleking in https://github.com/opentensor/bittensor/pull/2353
* add `Subtensor.register`, `Subtensor.difficulty` and related staff with tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2352
* added to Subtensor: `burned_register`, `get_subnet_burn_cost`, `recycle` and related extrinsics by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2359
* Poem "Risen from the Past". Act 3. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2363
* default port from 9946 to 9944 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2376
* remove unused prometheus extrinsic by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2378
* Replace rich.console to btlogging.loggin by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2377
* SDK (AsyncSubtensor) Part 1 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2374
* SDK (AsyncSubtensor) Part 2 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2380
* Handle SSL Error on Connection by @thewhaleking in https://github.com/opentensor/bittensor/pull/2384
* Avoid using `prompt` in SDK by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2382
* Backmerge/8.2.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2389
* Remove `retry` and fix tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2392
* fix: logging weights correctly in utils/weight_utils.py by @grantdfoster in https://github.com/opentensor/bittensor/pull/2362
* Add `subvortex` subnet and tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2395
* Release/8.2.1 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2397
* [Tests] AsyncSubtensor (Part 1) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2398
* Extend period for fastblock e2e tests_incentive.py by @opendansor in https://github.com/opentensor/bittensor/pull/2400
* Remove unused import by @thewhaleking in https://github.com/opentensor/bittensor/pull/2401
* `Reconnection substrate...` as debug by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2403
* Handles websockets v14+ in async by @thewhaleking in https://github.com/opentensor/bittensor/pull/2404
* [Tests] AsyncSubtensor (Part 2) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2407
* [Tests] AsyncSubtensor (Part 3) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2409
* Handle new PasswordError from btwallet by @thewhaleking in https://github.com/opentensor/bittensor/pull/2406
* [Tests] AsyncSubtensor (Part 4) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2410
* [Tests] AsyncSubtensor (Part 5) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2411
* Bringing back lost methods for setting weights by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2412
* Update bt-decode requirement by @thewhaleking in https://github.com/opentensor/bittensor/pull/2413
* [Tests] AsyncSubtensor (Part 6) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2414

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.2.1...v8.3.0

## 8.2.1 /2024-11-06

## What's Changed

* Expands the type registry to include all the available options by @thewhaleking in https://github.com/opentensor/bittensor/pull/2353
* add `Subtensor.register`, `Subtensor.difficulty` and related staff with tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2352
* added to Subtensor: `burned_register`, `get_subnet_burn_cost`, `recycle` and related extrinsics by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2359
* Poem "Risen from the Past". Act 3. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2363
* default port from 9946 to 9944 by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2376
* remove unused prometheus extrinsic by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2378
* Replace rich.console to btlogging.loggin by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2377
* Backmerge 8.2.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2389
* Add subvortex subnet and tests by @roman-opentensor  in https://github.com/opentensor/bittensor/pull/2395
* Handle SSL Error on Connection by @thewhaleking  in https://github.com/opentensor/bittensor/pull/2384
* Avoid using prompt in SDK by @roman-opentensor  in https://github.com/opentensor/bittensor/pull/2382

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.2.0...v8.2.1

## 8.2.0 /2024-10-10

## What's Changed
* remove commit from e2e tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2340
* add bittensor-cli as prod deps for sdk by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2345
* Fix the install command syntax by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/2346
* add config test by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2347
* Bumps version for 8.2.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2348

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.1.1...v8.2.0

## 8.1.1 /2024-10-04

## What's Changed
* Release/8.1.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2332
* Backmerge/8.1.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2341
* Bumps version and wallet by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2342

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v8.1.0...v8.1.1

## 8.1.0 /2024-10-03

## What's Changed
* Implements new logging level 'warning' by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2323
* Adds ConnectionRefusedError in-case of connection error by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2326
* Subtensor verbose False by default, debug logging for subtensor connected by @thewhaleking in https://github.com/opentensor/bittensor/pull/2335
* Fix tests to be ready for rust-based bittensor-wallet by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2336

## 8.0.0 /2024-09-25

## What's Changed

Removes Bittensor CLI and Wallet functionalities and changes the Bittensor SDK package to be light while maintaining backwards compatibility

* Update README.md by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/2320
* remove unused code (tensor.py-> class tensor), remove old tests, add new tests by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2311
* Updating/improving/creating docstring codebase by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2310
* README updates for SDK by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/2309
* Improved logic for concatenating message, prefix, and suffix in bittensor logging + test by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2306
* BTSDK: Implementation of substrait custom errors handler for bittensor by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2305
* btsdk cleanup by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2303
* Fix mypy error for btlogging by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2299
* Integrate `bt_decode` into BTSDK by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2298
* BTSDK: Corrected arguments order in logging methods + test by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2292
* BTSDK: removed exit sys call for ConnectionRefusedError in _get_substrate by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2288
* BTSDK: Move `do*` methods to related extrinsic by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2286
* add reconnection logic for correctly closed connection by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2283
* Move extrinsics, update `deprecated.py` module. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2278
* Add substrate reconnection logic by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2269
* Prod requirements cleanup by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2266
* Decoupling chain_data.py to sub-package by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2264
* Increase Bittensor SDK test coverage by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2262
* Increase SDK test coverage (Part3) by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2257
* Increase bittensor SDK test coverage by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2256
* Increase test coverage for subtensor.py by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2252
* Adds e2e and fixes metagraph save()/load() by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2231
* feat/roman/reafctoring-before-test-coverage by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2230
* Enhance: Switch from format() to f-strings by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2228
* Commit-reveal re-added & e2e coverage by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2224
* Adds e2e setup & tests by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2221
* Updates after review session by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2220
* Fix the usage of env vars in default settings. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2218
* Add dendrite reference to backwords compatibility by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2217
* Bringing `btsdk` up-to-date with `staging` branch. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2210
* Part 3: Create new 'bittensor-sdk` package by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2206
* Part 2: Redesign, fix namespace conflicts, remove btcli by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2204
* Part1: Removing content related to the wallet. Start use the pip installable package. by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2191

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.4.0...v8.0.0 

## 7.4.0 /2024-08-29

## What's Changed
* [Fix] Allow unstake below network min by @camfairchild in https://github.com/opentensor/bittensor/pull/2016
* Tests/e2e tests staging by @open-junius in https://github.com/opentensor/bittensor/pull/1943
* Chore: Backmerge 7.2 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2020
* Fix broken tests and Enforce BTCLI usage by @opendansor in https://github.com/opentensor/bittensor/pull/2027
* Add time delay to faucet by @opendansor in https://github.com/opentensor/bittensor/pull/2030
* Skip faucet test by @opendansor in https://github.com/opentensor/bittensor/pull/2031
* Adds normalization for alpha hyperparams by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2035
* Revert info logging in processing response by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2043
* Pin numpy version to 1.26.4 in prod.txt by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/2045
* Test hot key Swap by @opendansor in https://github.com/opentensor/bittensor/pull/2044
* Do not run Circle-CI on drafts by @thewhaleking in https://github.com/opentensor/bittensor/pull/1959
* Enhancement: Detailed nonce information in-case of failures by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2050
* fix bittensor not installing under Python 3.13 by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/2053
* Enable Faucet Test by @opendansor in https://github.com/opentensor/bittensor/pull/2056
* Add back BT_SUBTENSOR_CHAIN_ENDPOINT env variable by @bradleytf in https://github.com/opentensor/bittensor/pull/2034
* Fix: Logging configs not being set by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2065
* Feature/gus/liquid alpha params by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2012
* Test Emissions E2E by @opendansor in https://github.com/opentensor/bittensor/pull/2036
* Prevent e2e draft by @opendansor in https://github.com/opentensor/bittensor/pull/2072
* Fix e2e to only run when PR is ready for review by @opendansor in https://github.com/opentensor/bittensor/pull/2077
* Fix Faucet and fastblocks interaction by @opendansor in https://github.com/opentensor/bittensor/pull/2083
* Float normalization for child hotkeys by @opendansor in https://github.com/opentensor/bittensor/pull/2093
* Fix e2e test hanging by @open-junius in https://github.com/opentensor/bittensor/pull/2118
* Fixes leaked semaphores by @thewhaleking in https://github.com/opentensor/bittensor/pull/2125
* Backmerge master -> staging by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2136
* fix: coldkeypub usage instead of coldkey for arbitration_stats by @Rapiiidooo in https://github.com/opentensor/bittensor/pull/2132
* Removes extra no_prompts in commands by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2140
* Adds timeout for e2e tests by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2141
* fix: updates test_axon verify body async tests by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2142
* test: fix mocksubtensor query previous blocks by @timabilov in https://github.com/opentensor/bittensor/pull/2139
* Adds E2E for Metagraph command by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2143
* feat: Enhance dendrite error messaging by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2117
* Adds E2E Tests for wallet creation commands by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2145
* [Ledger Integration] [Feature] bump pysub to 1.7.9+ by @camfairchild in https://github.com/opentensor/bittensor/pull/2156
* Ruff complains about an extra line by @roman-opentensor in https://github.com/opentensor/bittensor/pull/2158
* support Wallet names with hyphens when passing password through ENV vars by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1949
* Fix naming convention of swap hotkey test by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2162
* Adds E2E test for wallet regenerations + fixes input bug for regen hotkey by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2149
* Backmerge Master -> Staging (7.4) by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2170
* ci: auto assigns cortex to opened PRs by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2184
* CI/E2E test improvements by @mvds00 in https://github.com/opentensor/bittensor/pull/2168
* Fix multiprocessing POW errors and No Torch logging errors by @thewhaleking in https://github.com/opentensor/bittensor/pull/2186
* ci: update reviewers by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2189
* Adds updated type in timeouts dendrite by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2196
* Bumps setuptools ~=70.0.0 by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2150
* Bump black from 23.7.0 to 24.3.0 in /requirements by @dependabot in https://github.com/opentensor/bittensor/pull/2197
* btlogging/loggingmachine.py: Fix bw compat API. by @mvds00 in https://github.com/opentensor/bittensor/pull/2155
* Check for participation before nomination call by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2193
* test: subnet list e2e by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2198
* ensure msg is str in _concat_msg by @thewhaleking in https://github.com/opentensor/bittensor/pull/2200
* Fixes tests depending on explicit line numbers by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2211
* Merge streaming fix to staging by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2183
* Multiple bittensor versions e2e workflow by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2212
* Changes name of workflow file by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2213
* Enhances e2e tests to contain assertions & logging  by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2192
* Security fix: Bumps ansible and certifi  by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2214
* Wallet List Command e2e test by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2207
* fix Synapse base performance (more than 10x speed up) by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/2161
* Child Hotkeys by @opendansor in https://github.com/opentensor/bittensor/pull/2071
* Improve child hotkeys QOL by @opendansor in https://github.com/opentensor/bittensor/pull/2225
* Child hotkeys handle excess normalization by @opendansor in https://github.com/opentensor/bittensor/pull/2229
* Fixes chain compilation timeouts by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2238
* Update Child Hotkey commands by @opendansor in https://github.com/opentensor/bittensor/pull/2245
* feat: return error message instead of raising exception by @gus-opentensor in https://github.com/opentensor/bittensor/pull/2244
* Backmerge master to staging (7.3.1) by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2254

## New Contributors
* @bradleytf made their first contribution in https://github.com/opentensor/bittensor/pull/2034
* @Rapiiidooo made their first contribution in https://github.com/opentensor/bittensor/pull/2132
* @timabilov made their first contribution in https://github.com/opentensor/bittensor/pull/2139
* @mvds00 made their first contribution in https://github.com/opentensor/bittensor/pull/2168
* @dependabot made their first contribution in https://github.com/opentensor/bittensor/pull/2197

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.3.1...v7.4.0

## 7.3.1 / 2024-08-19

## What's Changed
* https://github.com/opentensor/bittensor/pull/2156 by @camfairchild

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.3.0...v7.3.1

## 7.3.0 / 2024-07-12

## What's Changed
* Liquid Alpha by @opendansor & @gus-opentensor in https://github.com/opentensor/bittensor/pull/2012
* check_coldkey_swap by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/2126

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.2.0...v7.3.0


## 7.2.0 / 2024-06-12

## What's Changed
* less verbose handled synapse exceptions by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1928
* Clean up the imports in commands/stake.py by @thewhaleking in https://github.com/opentensor/bittensor/pull/1951
* Fix E2E test for Commit/Reveal with Salt flag by @opendansor in https://github.com/opentensor/bittensor/pull/1952
* `bittensor.chain_data.py` module refactoring. by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1955
* ci: e2e tests by @orriin in https://github.com/opentensor/bittensor/pull/1915
* Dependency cleanup by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1967
* replace `black` with `ruff` by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1968
* post-black to ruff migration cleanup by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1979
* Revert Axon IP decoding changes by @camfairchild in https://github.com/opentensor/bittensor/pull/1981
* A wrapper for presenting extrinsics errors in a human-readable form. by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1980
* Feat: Added normalized hyperparams by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1891
* deprecate nest_asyncio use by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1974
* Add e2e test for axon by @opendansor in https://github.com/opentensor/bittensor/pull/1984
* Dendrite E2E test by @opendansor in https://github.com/opentensor/bittensor/pull/1988
* fix __version_as_int__ for >10 minor/patch release vers (resolves #1982) by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1993
* Test Incentive E2E by @opendansor in https://github.com/opentensor/bittensor/pull/2002
* Add E2E faucet test by @opendansor in https://github.com/opentensor/bittensor/pull/1987
* Allow unstake below network min by @camfairchild in https://github.com/opentensor/bittensor/pull/2016

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.1.1...v7.2.0


## 7.1.1 / 2024-06-11

## What's Changed
* commit_reveal_weights_enabled argument parsing hotfix by @camfairchild in https://github.com/opentensor/bittensor/pull/2003

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.1.0...v7.1.1

## 7.1.0 / 2024-06-05

## What's Changed
* Added _do_set_root_weights by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1838
* Release/7.0.1 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1963

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.0.1...v7.1.0

## 7.0.1 / 2024-05-31

## What's Changed
* Release/7.0.0 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1899
* Fix return of ip version. by @opendansor in https://github.com/opentensor/bittensor/pull/1961
* Fix trigger use_torch() by @renesweet24 https://github.com/opentensor/bittensor/pull/1960

## New Contributors
* @renesweet24 made their first contribution in https://github.com/opentensor/bittensor/pull/1960

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v7.0.0...v7.0.1


## 7.0.0 / 2024-05-29

## What's Changed
* replace torch with numpy by @andreea-popescu-reef in https://github.com/opentensor/bittensor/pull/1777
* Fix broken link in contrib/RELEASE_GUIDELINES #1821 by @thewhaleking in https://github.com/opentensor/bittensor/pull/1823
* Tests: Added coverage for set_weights by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1825
* Remove irrelevant call to get_delegates method. by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1826
* Support for string mnemonic thru cli when regenerating coldkeys by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1815
* Logging: Added _primary_loggers by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1797
* Add in check for minimum stake for unstaking by @thewhaleking in https://github.com/opentensor/bittensor/pull/1832
* Cache get_decoder_class by @thewhaleking in https://github.com/opentensor/bittensor/pull/1834
* Warmfix/change decoder cacheing by @thewhaleking in https://github.com/opentensor/bittensor/pull/1842
* Fix typo in warmfix by @thewhaleking in https://github.com/opentensor/bittensor/pull/1844
* Add the command btcli root list_delegates_lite to handle the Delegate… by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1840
* Change: console.error => console.print by @thewhaleking in https://github.com/opentensor/bittensor/pull/1849
* Small fix with receiving delegates based on a 4-hour archive block by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1854
* Replace torch with numpy by @sepehr-opentensor in https://github.com/opentensor/bittensor/pull/1786
* Versioning: Enforcement for eth-utils by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1852
* Versioning: Dependencies for FastAPI for Apple M's by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1855
* Retrieving error types from the metadata of the Substrate palette SubtensorModule for the btcli console (logic) by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1862
* Add version check caching, fix version comparison by @olzhasar-reef in https://github.com/opentensor/bittensor/pull/1835
* Tests: Added coverage for root.py by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1877
* Tests: Added coverage for network.py by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1879
* Tests: extends coverage for overview cmd part 1 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1873
* Tests: Added coverage for Unstaking by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1878
* Tests: Added coverage for staking by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1837
* Tests: Added coverage for Delegation by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1874
* Updated error message and a test typo. by @thewhaleking in https://github.com/opentensor/bittensor/pull/1871
* fix: deprecated usage of `Balances::transfer` method by @orriin in https://github.com/opentensor/bittensor/pull/1886
* Fix Type Annotation by @opendansor in https://github.com/opentensor/bittensor/pull/1895
* Docstrings updates for list delegate lite feature by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1890
* Add Pre-commit Checker in scripts. Helps reduce CI calls. by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1893
* fix get_coldkey_password_from_environment resolving wrong password by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1843
* Drop python 3.8 support by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1892
* feat: Refactor phase 2 overview cmd & add test cov. Adds factories by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1887
* Add setting delegate take by @gztensor in https://github.com/opentensor/bittensor/pull/1903
* E2E Test Patterns by @orriin in https://github.com/opentensor/bittensor/pull/1885
* chore: correct method types by @distributedstatemachine in https://github.com/opentensor/bittensor/pull/1907
* bittensor.btlogging refactoring by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1896
* Part 1 for refactoring bittensor/subtensor.py by @RomanCh-OT in https://github.com/opentensor/bittensor/pull/1911
* Update: Pydantic V2 by @opendansor in https://github.com/opentensor/bittensor/pull/1889
* Add back compatibility with torch by @thewhaleking in https://github.com/opentensor/bittensor/pull/1904
* Release/6.12.2 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1910
* Chore: Updated dev requirements by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1946

## New Contributors
* @andreea-popescu-reef made their first contribution in https://github.com/opentensor/bittensor/pull/1777
* @thewhaleking made their first contribution in https://github.com/opentensor/bittensor/pull/1823
* @RomanCh-OT made their first contribution in https://github.com/opentensor/bittensor/pull/1826
* @olzhasar-reef made their first contribution in https://github.com/opentensor/bittensor/pull/1835
* @orriin made their first contribution in https://github.com/opentensor/bittensor/pull/1886
* @opendansor made their first contribution in https://github.com/opentensor/bittensor/pull/1895

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.12.2...v7.0.0

## 6.12.2 / 2024-05-20

## What's Changed
* Add setting delegate take
* fix: deprecated transfer method usage

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.12.1...54eee604c00ac4f04a31d5d7bc663124731a34d8


## 6.12.1 / 2024-05-17

## What's Changed
* Hotfix if the subnet UID is not in the Subnets


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.12.0...fd2442db8bb8aad55ced2ac3b748b04ebdc73292



## 6.12.0 / 2024-04-29

## What's Changed
* Tests: Axon to_string patch import by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1785
* Tests: Extends coverage on Serving extrinsics methods by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1783
* Fix: CVE-2024-24762 FastAPI by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1800
* Fix: CVE-2024-26130 | vulnerability cryptography by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1801
* fix PR templates by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1778
* Fix: SNYK-PYTHON-CERTIFI-5805047 | Vulnerability Certifi by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1816
* Tests: Extends test coverage on Registration methods by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1814
* Fix: Wallet overwrite functionality by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1802


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.11.0...v6.12.0

## 6.11.0 / 2024-04-11

## What's Changed
* Tests: Adds coverage to subtensor help method & determine_chain_endpoint_and_network by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1761
* [bug fix] Fix import json by @camfairchild in https://github.com/opentensor/bittensor/pull/1759
* Remove context management for substrate in subtensor by @sepehr-opentensor in https://github.com/opentensor/bittensor/pull/1766
* Tests: Extends coverage on axon methods by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1769
* Revert nonce implementation fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1774
* remove tests from package distribution by @mjurbanski-reef in https://github.com/opentensor/bittensor/pull/1779
* Tests: Extends test coverage on Senate methods by @ibraheem-opentensor in https://github.com/opentensor/bittensor/pull/1781

## New Contributors
* @mjurbanski-reef made their first contribution in https://github.com/opentensor/bittensor/pull/1779
* @ibraheem-opentensor made their first contribution in https://github.com/opentensor/bittensor/pull/1781

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.10.1...v6.11.0
## 6.10.1 / 2024-04-05
## What's Changed
* Revert nonce implementation fix #1774: Breaking change needs to telegraphed in next release.

## 6.10.0 / 2024-03-25

## What's Changed
* handle req args by parsing and raising by @ifrit98 in https://github.com/opentensor/bittensor/pull/1733
* Replace wildcard imports with specific imports by @brueningf in https://github.com/opentensor/bittensor/pull/1724
* Logging Refactor by @sepehr-opentensor in https://github.com/opentensor/bittensor/pull/1751
* Update DEBUGGING.md by @e-gons in https://github.com/opentensor/bittensor/pull/1755
* fix: nonce implementation by @GentikSolm in https://github.com/opentensor/bittensor/pull/1754

## New Contributors
* @sepehr-opentensor made their first contribution in https://github.com/opentensor/bittensor/pull/1751
* @e-gons made their first contribution in https://github.com/opentensor/bittensor/pull/1755
* @GentikSolm made their first contribution in https://github.com/opentensor/bittensor/pull/1754

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.9.3...v6.10.0

## 6.9.3 / 2024-03-12

## What's Changed
* Release/6.9.2 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1743


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.9.2...v6.9.3


## 6.9.2 / 2024-03-08

## What's Changed
* Change error into a warning if not using archive. Impossible to tell if local is lite or full node.


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.9.1...v6.9.2


## 6.9.1 / 2024-03-08

## What's Changed
* Hotfix for reversing comparison operator for block checking to raise error if not using archive nodes


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.9.0...v6.9.1


## 6.9.0 / 2024-03-07

## What's Changed
* Doc: Updates WalletBalanceCommand docstring by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1716
* feature: metapgraph.py now passing type check by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1721
* fix: Updates `btcli wallet balance --all` to get proper Wallet Name & Coldkey Address sets by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1720
* Feature/prompt set identity on btcli/phil by @ifrit98 in https://github.com/opentensor/bittensor/pull/1719
* Fix: Raises error when exceeding block max on metagraph by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1722
* Release/6.8.2 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1730
* Expands type checking to subtensor by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1731
* Feature: Synapse passing type check by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1725
* bump req for security vulnerability in crpytography by @ifrit98 in https://github.com/opentensor/bittensor/pull/1718
* Fix: proper association with wallet dir and coldkey addr #1739 by @gus-opentensor & @sepehr-opentensor
* Fixed event lookup on new network added #1741 by @shibshib

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.8.2...v6.9.0


## 6.8.2 / 2024-03-01

## What's Changed
* Set weights fix retry and check mechanism by @ifrit98 in https://github.com/opentensor/bittensor/pull/1729


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.8.1...v6.8.2


## 6.8.1 / 2024-02-22

## What's Changed
* Hotfix revert dendrite streaming call to use `synapse.process_streaming_response` func instead of Starlette `iter_any()` from response object.


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.8.0...v6.8.1


## 6.8.0 / 2024-02-16

## What's Changed
* Release/6.7.2 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1695
* close synchronosuly on __del__ by @ifrit98 in https://github.com/opentensor/bittensor/pull/1700
* CI: Flake8 by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1701
* logging off switch by @ifrit98 in https://github.com/opentensor/bittensor/pull/1704
* Extrinsic update by @ifrit98 in https://github.com/opentensor/bittensor/pull/1703
* Bittensor shared request layer by @ifrit98 in https://github.com/opentensor/bittensor/pull/1698
* Add no_prompt argument to help printout in https://github.com/opentensor/bittensor/pull/1707
* Adds mypi typechecking to circleci by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1705
* Remove set weights ttl now that we have a better extrinsic method by @ifrit98
* Bug fix in overview command for dereg stake with outdated `stake_info` object fields by @ifrit98 in https://github.com/opentensor/bittensor/pull/1712
* Moves mock wallet creation to temp dir by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1711


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.7.2...v6.8.0


## 6.7.2 / 2024-02-08

## What's Changed
* Release/6.7.1 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1688
* Increases test coverage for cli & chain_data by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1690
* Subtensor/update pysubstrate latest/phil by @ifrit98 in https://github.com/opentensor/bittensor/pull/1684
* Update staging to latest master by @ifrit98 in https://github.com/opentensor/bittensor/pull/1691
* return messages with subtensor extrinsic to set weights by @ifrit98 in https://github.com/opentensor/bittensor/pull/1692
* Logging/debug to trace axon by @ifrit98 in https://github.com/opentensor/bittensor/pull/1694


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.7.1...v6.7.2


## 6.7.1 / 2024-02-02

## What's Changed
* Release/6.7.0 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1674
* Eighth (final) docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1678
* Sixth docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1676
* Seventh docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1677
* Update README.md by @unconst in https://github.com/opentensor/bittensor/pull/1679
* Update README.md by @unconst in https://github.com/opentensor/bittensor/pull/1680
* black formatting by @ifrit98 in https://github.com/opentensor/bittensor/pull/1685
* burn -> recycle for public facing code by @ifrit98 in https://github.com/opentensor/bittensor/pull/1681
* Expands test coverage and coverts python unittest classes to pure pytest by @gus-opentensor in https://github.com/opentensor/bittensor/pull/1686
* wrap set weights in a ttl multiprocessing call so we don't hang past TTL by @ifrit98 in https://github.com/opentensor/bittensor/pull/1687

## New Contributors
* @gus-opentensor made their first contribution in https://github.com/opentensor/bittensor/pull/1686

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.7.0...v6.7.1



## 6.7.0 / 2024-01-25

## What's Changed
* First docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1663
* Second docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1665
* Third docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1666
* updated mac yaml mac yaml by @dougsillars in https://github.com/opentensor/bittensor/pull/1668
* Fourth docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1670
* Fifth docstrings formatting PR by @rajkaramchedu in https://github.com/opentensor/bittensor/pull/1671
* ensure branch off from staging and rm old docs by @ifrit98 in https://github.com/opentensor/bittensor/pull/1667
* staging black format fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1669
* wallet history url for taostats by @ifrit98 in https://github.com/opentensor/bittensor/pull/1672
* take bt.config as a first argument regardless if specified by @ifrit98 in https://github.com/opentensor/bittensor/pull/1664
* Hparams update by @ifrit98 in https://github.com/opentensor/bittensor/pull/1673

## New Contributors
* @rajkaramchedu made their first contribution in https://github.com/opentensor/bittensor/pull/1663
* @dougsillars made their first contribution in https://github.com/opentensor/bittensor/pull/1668

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.6.1...v6.7.0


## 6.6.1 / 2024-01-17

## What's Changed
* bittensor README update by @Jackalgirl in https://github.com/opentensor/bittensor/pull/1650
* Bugfix btcli fix args by @ifrit98 in https://github.com/opentensor/bittensor/pull/1654

## New Contributors
* @Jackalgirl made their first contribution in https://github.com/opentensor/bittensor/pull/1650

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.6.0...v6.6.1


## 6.6.0 / 2024-01-08

## What's Changed
* Add commitment support to MockSubtensor by @agoncharov-reef in https://github.com/opentensor/bittensor/pull/1635
* don't prenormalize weights in btcli boost/slash by @ifrit98 in https://github.com/opentensor/bittensor/pull/1636
* feat(wallets.py): add wallet history command by @saqib-codes-11 in https://github.com/opentensor/bittensor/pull/1638
* Update taostats link by @mogmachine in https://github.com/opentensor/bittensor/pull/1641
* update wallet history command to right justify and fmt 3 decimal places by @ifrit98 in https://github.com/opentensor/bittensor/pull/1639

## New Contributors
* @agoncharov-reef made their first contribution in https://github.com/opentensor/bittensor/pull/1635
* @saqib-codes-11 made their first contribution in https://github.com/opentensor/bittensor/pull/1638

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.5.0...v6.6.0


## 6.5.0 / 2023-12-19

## What's Changed
* Logging/axon handling refactor by @ifrit98 in https://github.com/opentensor/bittensor/pull/1627
* Add decoding to get_commitment helper function to return original value by @ifrit98 in https://github.com/opentensor/bittensor/pull/1630
* don't print subtensor message on cli by @ifrit98 in https://github.com/opentensor/bittensor/pull/1625
* Add tab autocompletion to btcli by @ifrit98 in https://github.com/opentensor/bittensor/pull/1628


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.4.4...v6.5.0


## 6.4.4 / 2023-12-14

## What's Changed

* Merge/master642 staging no-ff by @ifrit98 in https://github.com/opentensor/bittensor/pull/1615
* print help message on error for subcommands by @ifrit98 in https://github.com/opentensor/bittensor/pull/1618
* Metadata/commitments by @ifrit98 in https://github.com/opentensor/bittensor/pull/1621

## New Contributors
* @omahs made their first contribution in https://github.com/opentensor/bittensor/pull/1553
* @surcyf123 made their first contribution in https://github.com/opentensor/bittensor/pull/1569

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.4.2...v6.4.4


## 6.4.2 / 2023-12-07

## What's Changed
* Fix broken explorer links https://github.com/opentensor/bittensor/pull/1607
* Fix spamming bittensor subtensor logging https://github.com/opentensor/bittensor/pull/1608
* Fix hanging subtensor websocket https://github.com/opentensor/bittensor/pull/1609
* Hparam update to palette: https://github.com/opentensor/bittensor/pull/1612

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.4.1...v6.4.2


## 6.4.1 / 2023-12-01

## What's Changed
* add helpful messages to signal coming changes in https://github.com/opentensor/bittensor/pull/1600/commits/86c0c3ccfcd91d0e3ff87f53bdc3e9c5e68661da
* revert default subtensor network to finney in https://github.com/opentensor/bittensor/pull/1600/commits/8c69a3c15cd556384d0309e951f0a9b164dd36cb

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.4.0...v6.4.1


## 6.4.0 / 2023-11-29

## What's Changed
* (un)Staking multiple avoid tx limit by @camfairchild in https://github.com/opentensor/bittensor/pull/1244
* additional logging for prometheus by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1246
* Dataset fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1249
* Grab delegates details from GitHub by @camfairchild in https://github.com/opentensor/bittensor/pull/1245
* Add raw spec for local test and new bins by @camfairchild in https://github.com/opentensor/bittensor/pull/1243
* Fix list_delegates on non-archive nodes by @camfairchild in https://github.com/opentensor/bittensor/pull/1232
* Blacklist fixes + depreciation of old signatures by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1240
* [BIT-636] Change u16 weight normalization to max-upscaling by @opentaco in https://github.com/opentensor/bittensor/pull/1241
* remove duplicate command #1228 by @camfairchild in https://github.com/opentensor/bittensor/pull/1231
* test_forward_priority_2nd_request_timeout fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1276
* Remove btcli query and btcli set_weights by @camfairchild in https://github.com/opentensor/bittensor/pull/1144
* Merge releases 4.0.0 and 4.0.1 back to staging by @camfairchild in https://github.com/opentensor/bittensor/pull/1306
* Improve development workflow documentation by @quac88 in https://github.com/opentensor/bittensor/pull/1262
* staging updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1540
* Add root get_weights command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1536
* Fix typo by @steffencruz in https://github.com/opentensor/bittensor/pull/1543
* remove duplicated debug message in dendrite by @ifrit98 in https://github.com/opentensor/bittensor/pull/1544
* Cli fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1541
* update faucet helpstr by @ifrit98 in https://github.com/opentensor/bittensor/pull/1542
* Added mechanism to sum all delegated tao by @shibshib in https://github.com/opentensor/bittensor/pull/1547
* Dict hash fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1548
* Release/6.1.0 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1550
* Merge master by @ifrit98 in https://github.com/opentensor/bittensor/pull/1552
* Streaming fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1551
* Fix typos by @omahs in https://github.com/opentensor/bittensor/pull/1553
* Normalize weights in r get weights table by @camfairchild in https://github.com/opentensor/bittensor/pull/1556
* Dendrite & Synapse updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1555
* rm root flag in metagraph by @ifrit98 in https://github.com/opentensor/bittensor/pull/1558
* Max Faucet Runs == 3 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1560
* replace unknown wallet params (chain mismatch) with key values by @ifrit98 in https://github.com/opentensor/bittensor/pull/1559
* Remove PoW registration cli and associated extrinsic by @ifrit98 in https://github.com/opentensor/bittensor/pull/1557
* Add btcli wallet balance by @ifrit98 in https://github.com/opentensor/bittensor/pull/1564
* Dendrite fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1561
* Master into staging by @ifrit98 in https://github.com/opentensor/bittensor/pull/1570
* adding logging.exception by @surcyf123 in https://github.com/opentensor/bittensor/pull/1569
* Update network.py by @wildcommunist in https://github.com/opentensor/bittensor/pull/1568
* Subtensor Registry by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1562
* add instructions for upgrading bittensor with outdated version check by @ifrit98 in https://github.com/opentensor/bittensor/pull/1571
* Add identity commands to btcli by @ifrit98 in https://github.com/opentensor/bittensor/pull/1566
* Add set_delegate_take command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1563
* Subtensor archive by @ifrit98 in https://github.com/opentensor/bittensor/pull/1575
* Bugfix/list delegates by @ifrit98 in https://github.com/opentensor/bittensor/pull/1577
* don't return result twice in query() by @ifrit98 in https://github.com/opentensor/bittensor/pull/1574
* rename logging.py so doesn't circ import by @ifrit98 in https://github.com/opentensor/bittensor/pull/1572
* add AxonInfo.<to|from>_string() by @ifrit98 in https://github.com/opentensor/bittensor/pull/1565
* don't print __is_set for recursive objects by @ifrit98 in https://github.com/opentensor/bittensor/pull/1573
* Adds docstrings for CLI for Sphynx documentation by @ifrit98 in https://github.com/opentensor/bittensor/pull/1579
* Master 630 into staging by @ifrit98 in https://github.com/opentensor/bittensor/pull/1590
* Registry cost 0.1 tao by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1587
* Add swap_hotkey command to wallet by @ifrit98 in https://github.com/opentensor/bittensor/pull/1580
* Cuda fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1595
* Feature/local subtensor default by @ifrit98 in https://github.com/opentensor/bittensor/pull/1591
* Boost by @unconst in https://github.com/opentensor/bittensor/pull/1594
* avoid aiohttp <3.9.0 potential security issue by @ifrit98 in https://github.com/opentensor/bittensor/pull/1597
* update bittensor docstrings (overhaul) by @ifrit98 in https://github.com/opentensor/bittensor/pull/1592

## New Contributors
* @omahs made their first contribution in https://github.com/opentensor/bittensor/pull/1553
* @surcyf123 made their first contribution in https://github.com/opentensor/bittensor/pull/1569

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.1...v6.4.0


## 6.3.0 / 2023-11-16

## What's Changed
* (un)Staking multiple avoid tx limit by @camfairchild in https://github.com/opentensor/bittensor/pull/1244
* additional logging for prometheus by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1246
* Dataset fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1249
* Grab delegates details from GitHub by @camfairchild in https://github.com/opentensor/bittensor/pull/1245
* Add raw spec for local test and new bins by @camfairchild in https://github.com/opentensor/bittensor/pull/1243
* Fix list_delegates on non-archive nodes by @camfairchild in https://github.com/opentensor/bittensor/pull/1232
* Blacklist fixes + depreciation of old signatures by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1240
* [BIT-636] Change u16 weight normalization to max-upscaling by @opentaco in https://github.com/opentensor/bittensor/pull/1241
* remove duplicate command #1228 by @camfairchild in https://github.com/opentensor/bittensor/pull/1231
* test_forward_priority_2nd_request_timeout fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1276
* Remove btcli query and btcli set_weights by @camfairchild in https://github.com/opentensor/bittensor/pull/1144
* Merge releases 4.0.0 and 4.0.1 back to staging by @camfairchild in https://github.com/opentensor/bittensor/pull/1306
* Improve development workflow documentation by @quac88 in https://github.com/opentensor/bittensor/pull/1262
* staging updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1540
* Add root get_weights command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1536
* Fix typo by @steffencruz in https://github.com/opentensor/bittensor/pull/1543
* remove duplicated debug message in dendrite by @ifrit98 in https://github.com/opentensor/bittensor/pull/1544
* Cli fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1541
* update faucet helpstr by @ifrit98 in https://github.com/opentensor/bittensor/pull/1542
* Added mechanism to sum all delegated tao by @shibshib in https://github.com/opentensor/bittensor/pull/1547
* Dict hash fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1548
* Release/6.1.0 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1550
* Merge master by @ifrit98 in https://github.com/opentensor/bittensor/pull/1552
* Streaming fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1551
* Fix typos by @omahs in https://github.com/opentensor/bittensor/pull/1553
* Normalize weights in r get weights table by @camfairchild in https://github.com/opentensor/bittensor/pull/1556
* Dendrite & Synapse updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1555
* rm root flag in metagraph by @ifrit98 in https://github.com/opentensor/bittensor/pull/1558
* Max Faucet Runs == 3 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1560
* replace unknown wallet params (chain mismatch) with key values by @ifrit98 in https://github.com/opentensor/bittensor/pull/1559
* Remove PoW registration cli and associated extrinsic by @ifrit98 in https://github.com/opentensor/bittensor/pull/1557
* Add btcli wallet balance by @ifrit98 in https://github.com/opentensor/bittensor/pull/1564
* Dendrite fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1561
* Release/6.2.0 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1567
* Master into staging by @ifrit98 in https://github.com/opentensor/bittensor/pull/1570
* adding logging.exception by @surcyf123 in https://github.com/opentensor/bittensor/pull/1569
* Update network.py by @wildcommunist in https://github.com/opentensor/bittensor/pull/1568
* Subtensor Registry by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1562
* add instructions for upgrading bittensor with outdated version check by @ifrit98 in https://github.com/opentensor/bittensor/pull/1571
* Add identity commands to btcli by @ifrit98 in https://github.com/opentensor/bittensor/pull/1566
* Add set_delegate_take command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1563
* Subtensor archive by @ifrit98 in https://github.com/opentensor/bittensor/pull/1575
* Bugfix/list delegates by @ifrit98 in https://github.com/opentensor/bittensor/pull/1577
* don't return result twice in query() by @ifrit98 in https://github.com/opentensor/bittensor/pull/1574
* rename logging.py so doesn't circ import by @ifrit98 in https://github.com/opentensor/bittensor/pull/1572
* add AxonInfo.<to|from>_string() by @ifrit98 in https://github.com/opentensor/bittensor/pull/1565
* don't print __is_set for recursive objects by @ifrit98 in https://github.com/opentensor/bittensor/pull/1573

## New Contributors
* @omahs made their first contribution in https://github.com/opentensor/bittensor/pull/1553
* @surcyf123 made their first contribution in https://github.com/opentensor/bittensor/pull/1569

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.1...v6.3.0


## 6.2.0 / 2023-10-30

## What's Changed
* (un)Staking multiple avoid tx limit by @camfairchild in https://github.com/opentensor/bittensor/pull/1244
* additional logging for prometheus by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1246
* Dataset fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1249
* Grab delegates details from GitHub by @camfairchild in https://github.com/opentensor/bittensor/pull/1245
* Add raw spec for local test and new bins by @camfairchild in https://github.com/opentensor/bittensor/pull/1243
* Fix list_delegates on non-archive nodes by @camfairchild in https://github.com/opentensor/bittensor/pull/1232
* Blacklist fixes + depreciation of old signatures by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1240
* [BIT-636] Change u16 weight normalization to max-upscaling by @opentaco in https://github.com/opentensor/bittensor/pull/1241
* remove duplicate command #1228 by @camfairchild in https://github.com/opentensor/bittensor/pull/1231
* test_forward_priority_2nd_request_timeout fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1276
* Remove btcli query and btcli set_weights by @camfairchild in https://github.com/opentensor/bittensor/pull/1144
* Merge releases 4.0.0 and 4.0.1 back to staging by @camfairchild in https://github.com/opentensor/bittensor/pull/1306
* Improve development workflow documentation by @quac88 in https://github.com/opentensor/bittensor/pull/1262
* staging updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1540
* Add root get_weights command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1536
* Fix typo by @steffencruz in https://github.com/opentensor/bittensor/pull/1543
* remove duplicated debug message in dendrite by @ifrit98 in https://github.com/opentensor/bittensor/pull/1544
* Cli fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1541
* update faucet helpstr by @ifrit98 in https://github.com/opentensor/bittensor/pull/1542
* Added mechanism to sum all delegated tao by @shibshib in https://github.com/opentensor/bittensor/pull/1547
* Dict hash fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1548
* Release/6.1.0 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1550
* Merge master by @ifrit98 in https://github.com/opentensor/bittensor/pull/1552
* Streaming fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1551
* Fix typos by @omahs in https://github.com/opentensor/bittensor/pull/1553
* Normalize weights in r get weights table by @camfairchild in https://github.com/opentensor/bittensor/pull/1556
* Dendrite & Synapse updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1555
* rm root flag in metagraph by @ifrit98 in https://github.com/opentensor/bittensor/pull/1558
* Max Faucet Runs == 3 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1560
* replace unknown wallet params (chain mismatch) with key values by @ifrit98 in https://github.com/opentensor/bittensor/pull/1559
* Remove PoW registration cli and associated extrinsic by @ifrit98 in https://github.com/opentensor/bittensor/pull/1557
* Add btcli wallet balance by @ifrit98 in https://github.com/opentensor/bittensor/pull/1564
* Dendrite fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1561

## New Contributors
* @omahs made their first contribution in https://github.com/opentensor/bittensor/pull/1553

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.1...v6.2.0


## 6.1.0 / 2023-10-17

## What's Changed
* (un)Staking multiple avoid tx limit by @camfairchild in https://github.com/opentensor/bittensor/pull/1244
* additional logging for prometheus by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1246
* Dataset fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1249
* Grab delegates details from GitHub by @camfairchild in https://github.com/opentensor/bittensor/pull/1245
* Add raw spec for local test and new bins by @camfairchild in https://github.com/opentensor/bittensor/pull/1243
* Fix list_delegates on non-archive nodes by @camfairchild in https://github.com/opentensor/bittensor/pull/1232
* Blacklist fixes + depreciation of old signatures by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1240
* [BIT-636] Change u16 weight normalization to max-upscaling by @opentaco in https://github.com/opentensor/bittensor/pull/1241
* remove duplicate command #1228 by @camfairchild in https://github.com/opentensor/bittensor/pull/1231
* test_forward_priority_2nd_request_timeout fix by @isabella618033 in https://github.com/opentensor/bittensor/pull/1276
* Remove btcli query and btcli set_weights by @camfairchild in https://github.com/opentensor/bittensor/pull/1144
* Merge releases 4.0.0 and 4.0.1 back to staging by @camfairchild in https://github.com/opentensor/bittensor/pull/1306
* Improve development workflow documentation by @quac88 in https://github.com/opentensor/bittensor/pull/1262
* staging updates and fixes by @ifrit98 in https://github.com/opentensor/bittensor/pull/1540
* Add root get_weights command to btcli by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1536
* Fix typo by @steffencruz in https://github.com/opentensor/bittensor/pull/1543
* remove duplicated debug message in dendrite by @ifrit98 in https://github.com/opentensor/bittensor/pull/1544
* Cli fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1541
* update faucet helpstr by @ifrit98 in https://github.com/opentensor/bittensor/pull/1542
* Added mechanism to sum all delegated tao by @shibshib in https://github.com/opentensor/bittensor/pull/1547
* Dict hash fix by @ifrit98 in https://github.com/opentensor/bittensor/pull/1548


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.1...v6.1.0


## 6.0.1 / 2023-10-02

## What's Changed
* Fix requirements/prod.txt, we had a bad format dependency not allowed by PyPi by @eduardogr in https://github.com/opentensor/bittensor/pull/1537


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.0...v6.0.1


## 6.0.0 / 2023-10-02

## What's Changed
* - Adjusted blacklist argument default to False by @Inquinim in https://github.com/opentensor/bittensor/pull/1448
* Release/5.3.1 by @camfairchild in https://github.com/opentensor/bittensor/pull/1444
* Release/5.3.2 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1462
* [hotfix] Release v5.3.3 by @camfairchild in https://github.com/opentensor/bittensor/pull/1467
* Update README.md by @unconst in https://github.com/opentensor/bittensor/pull/1477
* Release/5.3.4 by @ifrit98 in https://github.com/opentensor/bittensor/pull/1483
* Revolution by @unconst in https://github.com/opentensor/bittensor/pull/1450


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.3.0...v6.0.0


## 6.0.1 / 2023-10-02

## What's Changed
* Fix requirements/prod.txt, we had a bad format dependency not allowed by PyPi by @eduardogr in https://github.com/opentensor/bittensor/pull/1537


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v6.0.0...v6.0.1


## 5.3.4 / 2023-08-16

# What's Changed
* Removes miniupnpc by @ifrit98 (completely unused and requires a sudo install)
* Fixes blacklist vpermit_required by @inquinim e80d3d5
* Add try/except and timeout to version checking with exception handles by @ifrit98 a6a89fd
* Further updates CONTRIBUTING.md and DEVELOPMENT_WORKFLOW.md by @gitphantomman 3fefdbb
* Adds automatic compatibility checks to circleci for all major python3 supported versions. add checks by @ifrit98 #1484

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.3.3...v5.3.4


## 5.3.3 / 2023-07-26

## What's Changed
* Remove datasets requirement by @camfairchild in 2eabf0002b01
* Relax bittensor-* requirements by @camfairchild in da9300ba5b2


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.3.2...v5.3.3


## 5.3.2 / 2023-07-25

## What's Changed
* Btlm miner by @shibshib in https://github.com/opentensor/bittensor/pull/1463
* Don't finalize set_weights ext by @camfairchild in https://github.com/opentensor/bittensor/pull/1461
* Faster overview pull by @camfairchild in https://github.com/opentensor/bittensor/pull/1464
* Contrib revamp by @ifrit98 in https://github.com/opentensor/bittensor/pull/1456
* fix torch typehint on some neurons BT-1329 by @camfairchild in https://github.com/opentensor/bittensor/pull/1460
* bump bittensor-wallet version to 0.0.5

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.3.1...v5.3.2


## 5.3.1 / 2023-07-06

 ## What's Changed
 * bump bittensor-wallet req, update cryptography security req by @@ifrit98 in [91d13b0](https://github.com/opentensor/bittensor/commit/91d13b0fa711621cbf823708d4368b1b387e42c4)
 * Fixes Discord Link Issue #1442  by @camfairchild in [54d6248](https://github.com/opentensor/bittensor/commit/54d62487d4cb59e0b5edcd53acdca013108d155b)
 * move mocks to bittensor_wallet package by @camfairchild in https://github.com/opentensor/bittensor/pull/1441
 * Bump bittensor-wallet version to 0.0.4

 **Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.3.0...v5.3.1

## 5.3.0 / 2023-07-04

## What's Changed
* [BIT-351] Ask for wallet name on btcli unstake by @camfairchild in https://github.com/opentensor/bittensor/pull/1387
* Fix tests using pure-Python MockSubtensor by @camfairchild in https://github.com/opentensor/bittensor/pull/1349
* Update README.md by @mostimasblunderbuss in https://github.com/opentensor/bittensor/pull/1397
* Update authint version by @ifrit98 in https://github.com/opentensor/bittensor/pull/1395
* Fix subtensor factory integration test by @camfairchild in https://github.com/opentensor/bittensor/pull/1400
* Remove neurons by @ifrit98 in https://github.com/opentensor/bittensor/pull/1389
* Merge pull request #1394 from opentensor/fix_axon_requests by @ifrit98 in https://github.com/opentensor/bittensor/pull/1406
* remove hotkey from proto and dendrite by @ifrit98 in https://github.com/opentensor/bittensor/pull/1407
* Weight Utils fix by @mrseeker in https://github.com/opentensor/bittensor/pull/1372
* Extract config to new package by @camfairchild in https://github.com/opentensor/bittensor/pull/1401
* Extract wallet by @camfairchild in https://github.com/opentensor/bittensor/pull/1403
* BTCli integration with new governance protocol by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1398
* Reverting unnecessary commits for next release. by @camfairchild in https://github.com/opentensor/bittensor/pull/1415
* Extract wallet and config by @camfairchild in https://github.com/opentensor/bittensor/pull/1411

## New Contributors
* @mostimasblunderbuss made their first contribution in https://github.com/opentensor/bittensor/pull/1397

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.2.0...v5.3.0


## 5.2.0 / 2023-06-28

## What's Changed
* add default 1024 max stake limit for querying UIDs with vpermit. by @ifrit98 in https://github.com/opentensor/bittensor/pull/1379
* Fixes validator permit issue seen on master by @unconst in https://github.com/opentensor/bittensor/pull/1381
* Added conda environment by @shibshib in https://github.com/opentensor/bittensor/pull/1386
* Update package requirements (hotfix) by @ifrit98 in https://github.com/opentensor/bittensor/pull/1385
* Merge master into new_staging by @ifrit98 in https://github.com/opentensor/bittensor/pull/1388
* Fix axon requests signature using metadata by @unconst in https://github.com/opentensor/bittensor/pull/1394
* Governance Protocol Release by @Rubberbandits in https://github.com/opentensor/bittensor/pull/1414


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.1.0...v5.2.0


## 5.1.0 / 2023-05-30

## What's Changed
* update readme by @unconst in https://github.com/opentensor/bittensor/pull/1344
* Reset scores for validators by @adriansmares in https://github.com/opentensor/bittensor/pull/1359


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v5.0.0...v5.1.0


## 5.0.0 / 2023-05-17

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v4.0.1...v5.0.0


## 4.0.1 / 2023-04-21

* Fix btcli my_delegates bug by @camfairchild in ef32a4da0d0827ab5977af1454d66ffe97cbc572
* Fix endpoint protocol check bug by @camfairchild and @Eugene-hu in https://github.com/opentensor/bittensor/pull/1296
* Fix changelog script and perms by @camfairchild in f5e7f1e9e9717d229fdec6875fdb9a3051c4bd6b and 1aed09a162ef0fe4d9def2faf261b15dc4c1fa8d

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v4.0.0...v4.0.1


## 4.0.0 / 2023-04-20

## What's Changed
* add mnrv-ai to delegates.json by @SFuller4 in https://github.com/opentensor/bittensor/pull/1226
* Update delegates list by @adriansmares in https://github.com/opentensor/bittensor/pull/1225
* Update delegates.json by @whiterhinoTAO in https://github.com/opentensor/bittensor/pull/1230
* Hotfix - Cli unstake fix by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1233
* Fix permissions for release github script by @eduardogr in https://github.com/opentensor/bittensor/pull/1224
* Staging into Release branch by @camfairchild in https://github.com/opentensor/bittensor/pull/1275
* Remove codecov by @camfairchild in https://github.com/opentensor/bittensor/pull/1282
* Use alt new preseal by @camfairchild in https://github.com/opentensor/bittensor/pull/1269

## New Contributors
* @SFuller4 made their first contribution in https://github.com/opentensor/bittensor/pull/1226
* @whiterhinoTAO made their first contribution in https://github.com/opentensor/bittensor/pull/1230

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.7.0...v4.0.0


## 3.6.3 / 2023-01-21

## What's Changed
* [hotfix][3.6.3] Fixing no version checking by @eduardogr in https://github.com/opentensor/bittensor/pull/1063


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.6.2...v3.6.3


## 3.6.2 / 2023-01-19

## What's Changed
* Hotfix/3.6.2/validator logit parameters by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1057


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.6.1...v3.6.2


## 3.6.1 / 2022-12-21

## What's Changed
* V3.6.0 nobunaga merge by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1028
* Integration dendrite test fixes by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1029
* Adding 3.6.0 release notes to CHANGELOG by @eduardogr in https://github.com/opentensor/bittensor/pull/1032
* [BIT-612] Validator robustness improvements by @opentaco in https://github.com/opentensor/bittensor/pull/1034
* [Hotfix 3.6.1] Validator robustness by @opentaco in https://github.com/opentensor/bittensor/pull/1035


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.6.0...v3.6.1


## 3.6.0 / 2022-12-13

## What's Changed
* Removal of dendrite multiprocessing by @Eugene-hu in https://github.com/opentensor/bittensor/pull/1017
* Merging back 3.5.1 fix to nobunaga by @eduardogr in https://github.com/opentensor/bittensor/pull/1018
* Release/3.5.0 post release by @eduardogr in https://github.com/opentensor/bittensor/pull/1010
* Fixes issue with --neuron.no_set_weights by @camfairchild in https://github.com/opentensor/bittensor/pull/1020
* Removing GitHub workflow push docker by @eduardogr in https://github.com/opentensor/bittensor/pull/1011
* [Fix] fix max stake for single by @camfairchild in https://github.com/opentensor/bittensor/pull/996
* [Feature] mention balance if not no prompt by @camfairchild in https://github.com/opentensor/bittensor/pull/995
* Add signature v2 format by @adriansmares in https://github.com/opentensor/bittensor/pull/983
* Improving the way we manage requirements by @eduardogr in https://github.com/opentensor/bittensor/pull/1003
* [BIT-601] Scaling law on EMA loss by @opentaco in https://github.com/opentensor/bittensor/pull/1022
* [BIT-602] Update scaling power from subtensor by @opentaco in https://github.com/opentensor/bittensor/pull/1027
* Release 3.6.0 by @eduardogr in https://github.com/opentensor/bittensor/pull/1023

## New Contributors
* @adriansmares made their first contribution in https://github.com/opentensor/bittensor/pull/976

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.5.1...v3.6.0


## 3.5.1 / 2022-11-24

## What's Changed
* [hotfix] pin scalecodec lower by @camfairchild in https://github.com/opentensor/bittensor/pull/1013


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.5.0...v3.5.1

## 3.5.0 / 2022-11-24

## What's Changed

- [Fix] allow synapse all (https://github.com/opentensor/bittensor/pull/988)
  - allow set synapse All using flag
  - add test
  - use dot get

- [Feature] Mark registration threads as daemons (https://github.com/opentensor/bittensor/pull/998)
  - make solver processes daemons

- [Feature] Validator debug response table (https://github.com/opentensor/bittensor/pull/999)
  - Add response table to validator debugging

- [Feature] Validator weight setting improvements (https://github.com/opentensor/bittensor/pull/1000)
  - Remove responsive prioritization from validator weight calculation
  - Move metagraph_sync just before weight setting
  - Add metagraph register to validator
  - Update validator epoch conditions
  - Log epoch while condition details
  - Consume validator nucleus UID queue fully
  - Increase synergy table display precision
  - Round before casting to int in phrase_cross_entropy
- small fix for changelog and version by @Eugene-hu in https://github.com/opentensor/bittensor/pull/993
- release/3.5.0 by @eduardogr in https://github.com/opentensor/bittensor/pull/1006

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.4.3...v3.5.0


## 3.4.3 / 2022-11-15

## What's Changed
* [Hotfix] Synapse security update by @opentaco in https://github.com/opentensor/bittensor/pull/991


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.4.2...v3.4.3

## 3.4.2 / 2022-11-09

## What's Changed
* Adding 3.4.0 changelog to CHANGELOG.md by @eduardogr in https://github.com/opentensor/bittensor/pull/953
* Release 3.4.2 by @unconst in https://github.com/opentensor/bittensor/pull/970


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.4.1...v3.4.2

## 3.4.1 / 2022-10-13

## What's Changed
* [Hotfix] Fix CUDA Reg update block by @camfairchild in https://github.com/opentensor/bittensor/pull/954


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.4.0...v3.4.1

## 3.4.0 / 2022-10-13

## What's Changed
* Parameters update by @Eugene-hu  #936
* Bittensor Generate by @unconst  #941
* Prometheus by @unconst  #928
* [Tooling][Release] Adding release script by @eduardogr in https://github.com/opentensor/bittensor/pull/948


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.3.4...v3.4.0


## 3.3.4 / 2022-10-03

### What's Changed
* [hot-fix] fix indent again. add test by @camfairchild in https://github.com/opentensor/bittensor/pull/907
* Delete old gitbooks by @quac88 in https://github.com/opentensor/bittensor/pull/924
* Release/3.3.4 by @Eugene-hu in https://github.com/opentensor/bittensor/pull/927

### New Contributors
* @quac88 made their first contribution in https://github.com/opentensor/bittensor/pull/924

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.3.3...v3.3.4


## 3.3.3 / 2022-09-06

### What's Changed
* [feature] cpu register faster by @camfairchild in https://github.com/opentensor/bittensor/pull/854
* [hotfix] fix flags for multiproc register limit by @camfairchild in https://github.com/opentensor/bittensor/pull/876
* Fix/diff unpack bit shift by @camfairchild in https://github.com/opentensor/bittensor/pull/878
* [Feature] [cubit] CUDA registration solver by @camfairchild in https://github.com/opentensor/bittensor/pull/868
* Fix/move overview args to cli by @camfairchild in https://github.com/opentensor/bittensor/pull/867
* Add/address CUDA reg changes by @camfairchild in https://github.com/opentensor/bittensor/pull/879
* [Fix] --help command by @camfairchild in https://github.com/opentensor/bittensor/pull/884
* Validator hotfix min allowed weights by @Eugene-hu in https://github.com/opentensor/bittensor/pull/885
* [BIT-552] Validator improvements (nucleus permute, synergy avg) by @opentaco in https://github.com/opentensor/bittensor/pull/889
* Bit 553 bug fixes by @isabella618033 in https://github.com/opentensor/bittensor/pull/886
* add check to add ws:// if needed by @camfairchild in https://github.com/opentensor/bittensor/pull/896
* [BIT-572] Exclude lowest quantile from weight setting by @opentaco in https://github.com/opentensor/bittensor/pull/895
* [BIT-573] Improve validator epoch and responsives handling by @opentaco in https://github.com/opentensor/bittensor/pull/901
* Nobunaga Release V3.3.3 by @Eugene-hu in https://github.com/opentensor/bittensor/pull/899


**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.3.2...v3.3.3

## 3.3.2 / 2022-08-18

### SynapseType fix in dendrite
### What's Changed
* SynapseType fix in dendrite by @robertalanm in https://github.com/opentensor/bittensor/pull/874

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.3.1...v3.3.2

## 3.3.1 / 2022-08-17

### What's Changed
* [hotfix] Fix GPU reg bug. bad indent by @camfairchild in https://github.com/opentensor/bittensor/pull/883

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.3.0...v3.3.1

## 3.3.0 / 2022-08-16

### CUDA registration
This release adds the ability to complete the registration using a CUDA-capable device.
See https://github.com/opentensor/cubit/releases/tag/v1.0.5 for the required `cubit` v1.0.5 release

Also a few bug fixes for the CLI

### What's Changed
* [hotfix] fix flags for run command, fix hotkeys flag for overview, and [feature] CUDA reg by @camfairchild in https://github.com/opentensor/bittensor/pull/877

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.2.0...v3.3.0

## 3.2.0 / 2022-08-12

### Validator saving and responsive-priority weight-setting

### What's Changed
* [BIT-540] Choose responsive UIDs for setting weights in validator + validator save/load by @opentaco in https://github.com/opentensor/bittensor/pull/872

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.1.0...v3.2.0

## 3.1.0 / 2022-08-11

### Optimizing multi-processed CPU registration
This release refactors the registration code for CPU registration to improve solving performance.

### What's Changed
* [feature] cpu register faster (#854) by @camfairchild in https://github.com/opentensor/bittensor/pull/875

**Full Changelog**: https://github.com/opentensor/bittensor/compare/v3.0.0...v3.1.0

## 3.0.0 / 2022-08-08

### Synapse update

##
