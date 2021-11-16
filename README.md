# Analysis of school performance of elementary and high school students in Brazil before and during the COVID-19 Pandemic
Project for the Specialization and Residence in Engineering and Data Science at the Centro de Informática - Universidade Federal de Pernambuco/Samsung

In this project, we analyzed the school performance and the school dropout rate for elementary and high school students in Brazil before and during the COVID-19 pandemic. We also developed an exploratory data analysis to answer our seven research questions to refute or corroborate the raised hypotheses. In our results, we showed that there was a significant impact of the pandemic on the school performance and school dropout rate of elementary and high school students in Brazil.

### Research Questions (RQ)

\begin{itemize}
    \item[\textbf{RQ1.}] Was there a change in approval and failure rate during the pandemic?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ2.}] Was approval and failure rate the same for elementary school and high school during the pandemic?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ3.}] Was approval and failure rate the same between public and private schools?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ4.}] Was approval and failure rate the same for urban and rural schools?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ5.}] Did the school dropout rate increase during the pandemic ?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ6.}] Was the school dropout rate the same in public and private schools?
\end{itemize}

\begin{itemize}
    \item[\textbf{RQ7.}] Was the school dropout rate the same in urban and rural schools?
\end{itemize}

## Installation


### Requirements

Use conda to install the requirements with:


```
conda env create -f requirements.yml --name covid-dashboard 
```

Activate the environment

```
conda activate covid-dashboard
```

## Obtaining data

Extract data in the first use

```
make get_data
```

Run the server

```
make run_server 
```
