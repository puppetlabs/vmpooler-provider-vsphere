# Changelog

## [3.4.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.4.0) (2026-03-17)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.3.4...3.4.0)

**Implemented enhancements:**

- \(P4DEVOPS-9438\) Wire circuit breaker into vSphere provider with connection timeouts [\#62](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/62) ([smahima27](https://github.com/smahima27))

**Fixed bugs:**

- \(RE-15750\) Handle vm no longer existing when attempting to migrate. [\#53](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/53) ([isaac-jha](https://github.com/isaac-jha))

**Merged pull requests:**

- \(maint\) Release prep 3.4.0 [\#63](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/63) ([smahima27](https://github.com/smahima27))
- Bump actions/github-script from 6 to 7 [\#60](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/60) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump actions/checkout from 3 to 4 [\#59](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/59) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump actions/setup-java from 3 to 4 [\#58](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/58) ([dependabot[bot]](https://github.com/apps/dependabot))

## [3.3.4](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.3.4) (2023-08-30)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.3.3...3.3.4)

**Fixed bugs:**

- \(maint\) Convert booleans and Time objects to strings when being added to redis [\#51](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/51) ([isaac-jha](https://github.com/isaac-jha))

## [3.3.3](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.3.3) (2023-08-28)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.3.2...3.3.3)

**Fixed bugs:**

- \(maint\) Update Gemfile.lock and use block for transaction. [\#49](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/49) ([isaac-jha](https://github.com/isaac-jha))

## [3.3.2](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.3.2) (2023-08-23)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.3.1...3.3.2)

**Fixed bugs:**

- \(maint\) Increase timeout for cloned vms to obtain IPs. [\#47](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/47) ([isaac-jha](https://github.com/isaac-jha))

## [3.3.1](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.3.1) (2023-08-22)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.3.0...3.3.1)

**Fixed bugs:**

- \(RE-15710\) Fix IP address that is returned and increase timeout [\#44](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/44) ([yachub](https://github.com/yachub))

## [3.3.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.3.0) (2023-08-18)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.2.0...3.3.0)

**Implemented enhancements:**

- \(POD-10\) Log reason for failed VM checks. [\#42](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/42) ([isaac-jha](https://github.com/isaac-jha))

## [3.2.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.2.0) (2023-08-10)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.1.0...3.2.0)

**Implemented enhancements:**

- Bump jruby to 9.4.3.0 and update lockfile [\#40](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/40) ([yachub](https://github.com/yachub))

**Merged pull requests:**

- Bump thor from 1.2.1 to 1.2.2 [\#38](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/38) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump vmpooler from 3.0.0 to 3.1.0 [\#37](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/37) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rack-test from 2.0.2 to 2.1.0 [\#36](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/36) ([dependabot[bot]](https://github.com/apps/dependabot))

## [3.1.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.1.0) (2023-05-01)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/3.0.0...3.1.0)

**Merged pull requests:**

- Migrate issue management to Jira [\#34](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/34) ([yachub](https://github.com/yachub))
- Bump jruby to 9.4.2.0 [\#33](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/33) ([yachub](https://github.com/yachub))

## [3.0.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/3.0.0) (2023-04-19)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/2.1.0...3.0.0)

**Breaking changes:**

- \(RE-15124\) Collect VMs IP for use with DNS Plugins [\#29](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/29) ([yachub](https://github.com/yachub))

## [2.1.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/2.1.0) (2023-03-06)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/2.0.0...2.1.0)

**Implemented enhancements:**

- \(RE-15161\) Use timeout builtin to TCPSocket when opening sockets. [\#30](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/30) ([isaac-jha](https://github.com/isaac-jha))

## [2.0.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/2.0.0) (2023-01-30)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/1.6.0...2.0.0)

**Implemented enhancements:**

- Migrate to rbvmomi2 [\#25](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/25) ([yachub](https://github.com/yachub))

**Closed issues:**

- Document Custom VM Attribute [\#23](https://github.com/puppetlabs/vmpooler-provider-vsphere/issues/23)

**Merged pull requests:**

- Fix workflow deprecations, changelog, and add docs [\#24](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/24) ([yachub](https://github.com/yachub))
- \(RE-15111\) Migrate Snyk to Mend Scanning [\#22](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/22) ([yachub](https://github.com/yachub))
- \(RE-14811\) Remove DIO as codeowners [\#21](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/21) ([yachub](https://github.com/yachub))
- Add Snyk action [\#20](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/20) ([yachub](https://github.com/yachub))
- Add release-engineering to codeowners [\#19](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/19) ([yachub](https://github.com/yachub))
- Update rubocop requirement from ~\> 1.1.0 to ~\> 1.28.2 [\#17](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/17) ([dependabot[bot]](https://github.com/apps/dependabot))

## [1.6.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/1.6.0) (2022-07-25)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/1.5.0...1.6.0)

**Merged pull requests:**

- pin to vmpooler 2.4 [\#18](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/18) ([sbeaulie](https://github.com/sbeaulie))

## [1.5.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/1.5.0) (2021-12-13)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/1.4.0...1.5.0)

**Merged pull requests:**

- Bump version to 1.5.0, require vmpooler \>= 2.1 [\#5](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/5) ([genebean](https://github.com/genebean))
- Move vsphere specific methods out of vmpooler [\#4](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/4) ([sbeaulie](https://github.com/sbeaulie))

## [1.4.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/1.4.0) (2021-12-08)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/1.3.0...1.4.0)

**Merged pull requests:**

- Prep for initial standalone release: v1.4.0 [\#3](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/3) ([genebean](https://github.com/genebean))
- Add GH Action for releasing gems [\#2](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/2) ([genebean](https://github.com/genebean))
- Fix naming, add docs, add missing test file [\#1](https://github.com/puppetlabs/vmpooler-provider-vsphere/pull/1) ([genebean](https://github.com/genebean))

## [1.3.0](https://github.com/puppetlabs/vmpooler-provider-vsphere/tree/1.3.0) (2021-11-29)

[Full Changelog](https://github.com/puppetlabs/vmpooler-provider-vsphere/compare/a08cba099f867b1db01a50940ec3ae9239245db5...1.3.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
