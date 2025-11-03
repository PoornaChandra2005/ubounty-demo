# UBounty 🚀

> Create & fund a GitHub bounty in **15 seconds** — no account, no KYC, no friction.

---

## 🕒 How fast is fast?

**Time it yourself:**

1. Copy-paste any public GitHub issue URL  
2. Choose your crypto + amount  
3. Confirm transaction

✅ Bounty is live, funds are locked — instantly on-chain.

---

## 🎯 Why UBounty?

Most bounty platforms feel like paperwork. UBounty is different:

- **No signup** — just connect your wallet.
- **No escrow headaches** — funds are auto-locked via the [x402 protocol].
- **No delay** — bounties go live in seconds, not days.
- **No permission needed** — works with any public GitHub repo.

---

## ⚙️ How it works

| Step | Action | Time |
|------|--------|------|
| 1    | Paste GitHub issue URL | 3s |
| 2    | Enter amount + token | 4s |
| 3    | Confirm via wallet | 8s |
| ✅    | **Bounty goes live** | **~15s total** |

---

## 🔍 Under the hood

UBounty is powered by the open **x402 protocol**, enabling trustless on-chain bounties designed for developers.

- Funds are held in smart contracts until completion
- Completely on-chain — transparent and auditable
- Can be integrated in any Web3 or Web2 workflow


## Core Logic:

- How should developers claim bounties and link their wallet address? → auto-detect PR merge, dev can link their wallet in the setting. 
- What happens if multiple developers submit PRs for the same bounty? → Support splitting payment across multiple PRs
- How should we detect when a PR is merged? → GitHub webhook (automatic, real-time)  
- Should developers be able to claim a bounty BEFORE starting work? → No - only track after PR merge
