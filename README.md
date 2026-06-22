<img align="left" src="icon/icon-readme.png" alt="icon">

# [@xamidi/pmData](https://github.com/xamidi/pmData)

A curated list of proof systems based on detachment (so-called Hilbert systems), with analyses, proof data, and logs.

Exhaustive and refined proof collections were generated and can be processed with [pmGenerator](https://github.com/xamidi/pmGenerator). Large, highly compressed proof files are hosted on cloud servers. They are made available via download links. Smaller files are hosted here or on the *pmGenerator* page for demonstration purposes.

Sharing data in this manner enables researchers to build upon past work rather than constantly reinventing the wheel.

## Classical Implicational Logic

| System | Fragment | Number of Symbols | Axioms |
| :-- | :--: | --: | :-- |
| [Łukasiewicz's implicational axiom](sys/CCCpqrCCrpCsp#readme) | C | 13 (minimal 1‑basis) | ((ψ→φ)→χ)→((χ→ψ)→(ξ→ψ)) |

## Classical Logic

| System | Fragment | Number of Symbols | Axioms |
| :-- | :--: | --: | :-- |
| [Łukasiewicz's implicational axiom with the principle of explosion](sys/CCCpqrCCrpCsp,COp#readme) | C-O | 13+3 = 16<br>(minimal 2‑basis) | ((ψ→φ)→χ)→((χ→ψ)→(ξ→ψ))<br>⊥→ψ |
| [Meredith's axiom](https://xamidi.github.io/pmGenerator/README.html#merediths-axiom-1-basis-cccccpqcnrnsrtcctpcsp-top1000-cardinalities-nd-sample-info)   | C-N | 21 (minimal 1‑basis) | ((((ψ→φ)→(¬χ→¬ξ))→χ)→τ)→((τ→ψ)→(ξ→ψ)) |
| [Walsh's 1st axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-1st-axiom-1-basis-ccpccnpqrcsccntcrtcpt-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | (ψ→((¬ψ→φ)→χ))→(ξ→((¬τ→(χ→τ))→(ψ→τ))) |
| [Walsh's 2nd axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-2nd-axiom-1-basis-cpccqcprccnrccnstqcsr-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | ψ→((φ→(ψ→χ))→((¬χ→((¬ξ→τ)→φ))→(ξ→χ))) |
| [Walsh's 3rd axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-3rd-axiom-1-basis-cpccnqccnrscptcctqcrq-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | ψ→((¬φ→((¬χ→ξ)→(ψ→τ)))→((τ→φ)→(χ→φ))) |
| [Walsh's 4th axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-4th-axiom-1-basis-cpccnqccnrsctqccrtcrq-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | ψ→((¬φ→((¬χ→ξ)→(τ→φ)))→((χ→τ)→(χ→φ))) |
| [Walsh's 5th axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-5th-axiom-1-basis-ccpqcccrcstcqcnsnpcps-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | (ψ→φ)→(((χ→(ξ→τ))→(φ→(¬ξ→¬ψ)))→(ψ→ξ)) |
| [Walsh's 6th axiom](https://xamidi.github.io/pmGenerator/README.html#walshs-6th-axiom-1-basis-cccpqcccnrnsrtcctpcsp-top1000-cardinalities-nd-sample-info) | C-N | 21 (minimal 1‑basis) | ((ψ→φ)→(((¬χ→¬ξ)→χ)→τ))→((τ→ψ)→(ξ→ψ)) |
| Łukasiewicz (L₁)-system<br>(no data apart from [luk‑pmproofs](https://github.com/xamidi/luk-pmproofs)) | C-N | 11+6+6 = 23<br>(smallest known 3‑basis) | (ψ→φ)→((φ→χ)→(ψ→χ))<br>(¬ψ→ψ)→ψ<br>ψ→(¬ψ→φ) |
| [Łukasiewicz (L₃)-system](https://xamidi.github.io/pmGenerator/README.html#freges-calculus-simplified-by-%C5%82ukasiewicz-cpcqpccpcqrccpqcprccnpnqcqp-top1000-cardinalities-db-customization-info) | C-N | 5+13+9 = 27 | ψ→(φ→ψ)<br>(ψ→(φ→χ))→((ψ→φ)→(ψ→χ))<br>(¬ψ→¬φ)→(φ→ψ) |

## Classical Modal Logic

| System | Fragment | Number of Symbols | Axioms |
| :-- | :--: | --: | :-- |
| [S5 (extension of Łukasiewicz (L₃)‑system)](https://xamidi.github.io/pmGenerator/README.html#s5-cpcqpccpcqrccpqcprccnpnqcqpclppclcpqclplqcnlnplnlnp-top1000-cardinalities-db-sample-info) | C-N-L  | 5+13+9+4+10+10 = 51 | ψ→(φ→ψ)<br>(ψ→(φ→χ))→((ψ→φ)→(ψ→χ))<br>(¬ψ→¬φ)→(φ→ψ)<br>□ψ→ψ<br>□(ψ→φ)→(□ψ→□φ)<br>¬□¬ψ→□¬□¬ψ  [alias ◇ψ→□◇ψ] |
