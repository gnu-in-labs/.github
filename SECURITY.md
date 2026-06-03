# Security Policy

GNU.IN work is experimental and still becoming public in stages. Security reports are welcome, but the project should not imply mature enterprise support or stable public releases before that evidence exists.

## Supported Versions

There are no broadly supported stable releases yet.

| Channel | Security status |
| --- | --- |
| Public organization/profile files | Best-effort review |
| Experimental GNU.IN OS work | Best-effort review while public-readiness is being prepared |
| Undocumented local installs, forks, or private runtime modifications | Not supported |

Future public releases should define their own support window, verification instructions, and end-of-support policy.

## Reporting a Vulnerability

Please do not open a public issue for a vulnerability.

Email:

- `security@gnu6.live`
- `admin@gnu6.live`

Include, when possible:

- affected repository or surface;
- steps to reproduce;
- expected impact;
- logs, screenshots, or proof of concept if safe to share;
- whether the issue is already public.

We aim to acknowledge reports quickly, but response time is best-effort while the project is early.

## Security Stance

GNU.IN uses automation and agents as tools for inspection, drafting, and staging. They should not become final authority over live systems.

Security-sensitive changes should be explicit about:

- shell execution;
- secrets;
- network calls;
- D-Bus, IPC, or socket authority;
- local runtime mutation;
- build, release, and promotion boundaries;
- rollback paths.
