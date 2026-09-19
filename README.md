| `get_vc_count(subject)` | Returns the total number of anchored VCs, including revoked ones. |
| `get_active_vc_count(subject)` | Returns the number of non-revoked VCs — the count used internally by `compute_score`. |

*Note: Feeders and lenders should use `get_active_vc_count` when fetching VC counts for scoring.*