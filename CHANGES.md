## v0.1.1 (2024-07-05)
- Improve documentation
- Allow nixos as distribution (@patricoferris, @RyanGibb)
- Add XDP support (@Hevienz)
  - `bpf_xdp_attach`
  - `bpf_xdp_detach`

## v0.1.0 (2024-07-01)
- Initial release.

	`ocaml_libbpf`:
	- [supported](./supported.json) bindings
	- high level API's for open/load/attach/teardown

	`ocaml_libbpf_maps`:
	- high level API's for BPF ring_buffer map
