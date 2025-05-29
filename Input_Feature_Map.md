# Feature Log: `inp.json` Parameters
**Sorted by Feature / Module**  
(*Names link to author GitHub commit history*)

---

##  `core`

- `MaxNoofC180s` – [Pranav](https://github.com/pmadhikar)  
- `MaxBuffer` – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
- `particle_mass`, `repulsion_range`, `attraction_range`, `repulsion_strength`, `attraction_strength`, `Youngs_mod` – [Pranav](https://github.com/pmadhikar)  
- `stiffFactor1`, `internal_damping`, `viscotic_damping`, `gamma_visc` – [Pranav](https://github.com/pmadhikar), modified by [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)  
- `shear_rate` – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
- `division_Vol`, `div_time_steps`, `time_interval` – [Pranav](https://github.com/pmadhikar)  
- `Restart`, `trajWriteInt`, `non_div_time_steps`, `trajFileName` – [Pranav](https://github.com/pmadhikar)  
- Output toggles:  
  - `write_vel_file`, `write_for_file`, `write_traj_file`, `write_cm_file`, `write_vcm_file`, `write_fcm_file` – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
  - `write_extra_force_file`, `Extra_Forces_file` – [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)  
- Force and motion control:  
  - `correct_com` – [Pranav](https://github.com/pmadhikar)  
  - `correct_Vcom` – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
  - `Polarity`, `angleConst` – introduced by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei), updated by [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)  
- Pressure control and growth:  
  - `maxPressure`, `minPressure`, `growth_rate` – [Pranav](https://github.com/pmadhikar)

---

## `counting`

- `countcells`, `radius_cutoff`, `cell_count_int`, `count_only_internal_cells?`, `overwrite_mit_ind_file?`, `mit-index_file_name` – [Pranav](https://github.com/pmadhikar)

---

##  `population`

- All parameters – [Pranav](https://github.com/pmadhikar)

---

## ⚐️ `apoptosis`  
(*Full apoptosis module*)  
- Introduced by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)

---

## 🧵 `ECMparams`  
(*Full ECM module*)  
- Introduced by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)

---

## 🧬 `divParams`

- Basic division plane control – [Pranav](https://github.com/pmadhikar)  
- `Random_Div_Rule`, `Fibre`, `Rotation_angle`, `Rotation_rate`, `asymDivision` – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
- `along_Major_axis` – [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)

---

## 🦢 `NewCell`  
(*Full section*)  
- Added by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)

---

## 🧪 `ColloidParams`  
(*Full section*)  
- Added by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)

---

## 📦 `boxParams`

- Basic box setup – [Pranav](https://github.com/pmadhikar)  
- Rigid box toggles, impurity options, adhesion – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)  
- `Surface_friction`, `gamma_surface` – [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)

---

## 🎲 `rand_params`

- Original noise support – [Pranav](https://github.com/pmadhikar)  
- Enabled for ECM + simulation variants – [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei)

---

## 🌊 `Fluid`  
(*Full section*)  
- Added by [Mahmood](https://github.com/SoftSimu/CellSim3D/commits?author=MMazarei), extended by [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)

---

## 🚒 `Initial_shape`

- Entire section introduced by [Yasamin](https://github.com/SoftSimu/CellSim3D/commits?author=yasamino)
