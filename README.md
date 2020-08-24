# Indian-eSIR-model

The Coronavirus Disease or __COVID-19__ had been declared a pandemic by the World Health Organisation. It is a highly infectious disease caused by the Novel Coronavirus SARS-CoV-2 for which no vaccine has been developed yet. This disease is transmitted by inhalation or contact with infected droplets or fomites, and the incubation period may range from 2 to 14 days. Based on the data from China, the World Health Organisation (WHO) says, on average, a person recovers from Covid-19 in 14 days. It is spreading throughout the globe at a rapid pace and has already caused the destruction of an unprecedented scale, economically, physically, and socially. 
 
With no cure in the immediate future and no immediate possibility of vaccine development (commercial use of a vaccine could take twelve to eighteen months), the Government of India had to rely on suppressive measures such as national lockdown to contain the virus. The purpose of the lockdown is to slow down the spread of the coronavirus so that it doesn’t break the already fragile Indian Healthcare System.
 
[This](https://iimv.ac.in/research/covid-19-research) paper models the spread of the coronavirus. The predictions can be used to form Government policies to contain the virus and to be better prepared for what’s about to come mentally, physically and economically.
 
 ### Epidemiological Model: SIR
 
The Susceptible-Infected-Recovered/Removed (__SIR__) model is a very basic model in Epidemiology to predict the spread of an infectious disease. The susceptible compartment consists of people who are vulnerable to the disease, and in the case of Covid-19, it is the entire population except those who have gained immunity after recovering. The basic SIR model calculates the rate of susceptibility, rate of infected, rate of removed (recovered + dead) by considering the solution of the function where Y<sub>t</sub><sup>I</sup> and Y<sub>t</sub><sup>R</sup> (proportions of infected and removed state at time t) follows a Beta-Dirichlet state-space model (BDSSM). A fourth-order approximation is then applied to the solution. The differential equations governing the model are:



The drawback of the SIR model is that it considers a constant transmission rate β throughout the course of the epidemic and does not consider any adopted individual or government measures.

Our aim is to reduce the transmission rate β or increase the recovery rate γ. As the recovery rate depends on the arrival of the vaccine and the immunity power, we intend to reduce the transmission rate to as low as possible such that the ratio β/γ is less than one. (i.e., the recovery rate is larger than the transmission rate.) This ratio is denoted by R<sub>0</sub> called the Basic Reproductive Number. This ratio is dynamic and can change w.r.t the measures and social distancing being followed. 

The real-time function denoted by R<sub>t</sub>(Effective Reproductive Number), defined as the average number of secondary infections produced by an infected individual when transmission occurs in a population that is not entirely susceptible due to implemented control measures is calculated by a method which requires only the daily number of observed reported cases and the distribution of Serial Interval. (The time between successive cases in a chain of transmission.) This real-time ratio helps us in deciding future severity and possible steps to reduce fatalities.
