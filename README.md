# Online_EV_charging_coordination
An open-access online optimization framework to minimize CO2 emissions from multiple EV charging


To conduct online optimization, open the Main_ONCC via Juypter Notebook and run. Main_OFCC serves as the benchmark offline algorithm for comparison.


# The usage of other files:

func_EVC: Data cleaning & Construct EV charging session datasets for running the simulation

func_existing load: Data cleaning & Construct the existing electrical load dataset for running the simulation

plot_emission_mitigation: Plot the figures about the results of emission mitigation after coordination

plot_load_profile: Plot the figures about the results of the load profile after and before coordination

plot_compo_dates: Plot the composition of the day types of the data used in the simulation

source_data: contains the source data files for the entire simulation

base_load: Output of func_existing load

EVC: Output of func_EVC

EV_charging_load_demand: contains the EV charging demand profiles from the simulation of the online algorithm (Output of Main_ONCC)

EV_charging_load_ofcc: contains the EV charging load from the simulation of the offline algorithm (Output of Main_OFCC)

EV_charging_load_uc: contains the EV charging load from the uncontrolled charging (Output of Main_ONCC)

pareto_oncc: contains the results of emission mitigation from the simulation of the online algorithm (Output of Main_ONCC)


# All the source data used in this study are open access. The references are as follows.

U.S. Energy Information Administration, 2022. Electric System Operating Data. https://www.eia.gov/opendata/v1/qb.php?category=2123635 (accessed on 15 Oct. 2023).

U.S. Energy Information Administration. Annual state electricity profiles. https://www.eia.gov/electricity/state/; 2022 (accessed on 15 Oct. 2023).

Luo N, Wang Z, Blum D, Weyandt C, Bourassa N, Piette MA, et al. A three-year dataset supporting research on building energy management and occupancy analytics. Sci Data 2022;9:156. https://doi.org/10.1038/s41597-022-01257-x.

Lee ZJ, Li T, Low SH. ACN-data: Analysis and applications of an open EV charging dataset. Proc. Tenth ACM Int. Conf. Futur. Energy Syst., 2019, p. 139–49.

Kang Z, Ye Z, Hsu S-C. Developing an hourly-resolution well-to-wheel carbon dioxide emission inventory of electric vehicles. Resour Conserv Recycl 2023;190:106819.
