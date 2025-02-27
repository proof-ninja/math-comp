# Changelog (unreleased)

To avoid having old PRs put changes into the wrong section of the CHANGELOG,
new entries now go to the present file as discussed
[here](https://github.com/math-comp/math-comp/wiki/Agenda-of-the-April-23rd-2019-meeting-9h30-to-12h30#avoiding-issues-with-changelog).

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added

- in `seq.v`
  + lemmas `subset_mapP`, `take_min`, `take_taker`

- in `path.v` 
  + lemmas `prefix_path`, `prefix_sorted`, `infix_sorted`, `suffix_sorted` 

- in `ssralg.v`
  + lemmas `natr1`, `nat1r`

- in `poly.v`
  + definitions `even_poly`, `odd_poly`, `take_poly`, `drop_poly`
  + lemmas `comm_polyD`, `comm_polyM`, `comm_poly_exp`, `root_exp`,
    `root_ZXsubC`, `size_mulXn`, `coef_sumMXn`, `comp_Xn_poly`,
    `coef_comp_poly_Xn`, `comp_poly_Xn`, `size_even_poly`,
    `size_even_poly_eq`, `coef_even_poly`, `even_polyE`, `even_polyD`,
    `even_polyZ`, `even_poly_is_linear`, `even_polyC`,
    `size_odd_poly`, `coef_odd_poly`, `odd_polyE`, `odd_polyC`,
    `odd_polyD`, `odd_polyZ`, `odd_poly_is_linear`, `odd_polyMX`,
    `even_polyMX`, `sum_even_poly`, `sum_odd_poly`, `poly_even_odd`,
    `size_take_poly`, `coef_take_poly`, `take_poly_id`, `take_polyD`,
    `take_polyZ`, `take_poly_is_linear`, `take_poly_sum`,
    `take_poly0l`, `take_poly0r`, `take_polyMXn`, `take_polyMXn_0`,
    `take_polyDMXn`, `size_drop_poly`, `size_drop_poly_eq`,
    `coef_drop_poly`, `drop_poly_eq0`, `sum_drop_poly`, `drop_polyD`,
    `drop_polyZ`, `drop_poly_is_linear`, `drop_poly_sum`,
    `drop_poly0l`, `drop_poly0r`, `drop_polyMXn`, `drop_polyMXn_id`,
    `drop_polyDMXn`, `poly_take_drop`, `eqp_take_drop`
  + canonical instances `even_poly_additive`, `even_poly_linear`,
    `odd_poly_additive`, `odd_poly_linear`, `take_poly_additive`,
    `take_poly_linear`, `drop_poly_additive`, `drop_poly_linear`

- in `polydiv.v`
  + lemmas `Pdiv.RingMonic.drop_poly_rdivp`,
    `Pdiv.RingMonic.take_poly_rmodp`,
    `Pdiv.IdomainMonic.drop_poly_divp`,
    `Pdiv.IdomainMonic.take_poly_modp`

- in `bigop.v`
  + lemmas `big_ord1_eq`, `big_ord1_cond_eq`, `big_nat1_eq`,
    `big_nat1_cond_eq`

- in `seq.v`
  + lemma `if_nth`

- in `ssrbool.v`
  + lemmas `if_and`, `if_or`, `if_implyb`, `if_impliybC`, `if_add`

- in `ssralg.v`
  + lemma `eqr_sum_div`

- in `ssrnum.v`
  + lemmas `psumr_neq0`, `psumr_neq0P`

- in `ssrnat.v`
  + lemma `leqVgt`
  + lemmas `ltn_half_double`, `leq_half_double`, `gtn_half_double`
  + lemma `double_pred`
  + lemmas `uphalfE`, `ltn_uphalf_double`, `geq_uphalf_double`, `gtn_uphalf_double`
  + lemmas `halfK`, `uphalfK`, `odd_halfK`, `even_halfK`, `odd_uphalfK`, `even_uphalfK`
  + lemmas `leq_sub2rE`, `leq_sub2lE`, `ltn_sub2rE`, `ltn_sub2lE`

- in `ssrint.v`
  + printing only notation for `x = y :> int`, opening `int_scope` on
    `x` and `y` to better match the already existing parsing only
    notation with the introduction of number notations in `ring_scope`

### Changed

- in `poly.v`:
  + generalize `eq_poly`

- in `poly.v`:
  + made hornerE preserve powers

### Renamed

### Removed

### Infrastructure

### Misc

