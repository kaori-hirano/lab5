# Data for Lab 5 - Comparing Ridge, Lasso, and OLS

Player salary data was scraped from the MLS Players’ Association
[website](https://mlsplayers.org/resources/salary-guide). Player
statistics were scraped from <https://fbref.com/>.

### Codebook

<div class="cell-output-display">

| Variables                 | Description                                                                                                                                                                    |
|:--------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `Player`                  | Player’s full name                                                                                                                                                             |
| `Nation`                  | Player’s nation of birth or registered FIFA nation                                                                                                                             |
| `Pos`                     | Position played by player (can be multiple; if so, separated by commas)                                                                                                        |
| `Age`                     | Player’s age                                                                                                                                                                   |
| `MP`                      | Number of games played in 2022 MLS season                                                                                                                                      |
| `Starts`                  | Number of games started in 2022 MLS season                                                                                                                                     |
| `Min`                     | Number of minutes played in 2022 MLS season                                                                                                                                    |
| `nineties`                | How many 90 minutes player completed. This column is a linear combination of the `Min` column. `nineties` = `Min`/90                                                           |
| `Gls`                     | Goals scored in 2022 MLS season                                                                                                                                                |
| `Ast`                     | Assissts in 2022 MLS season                                                                                                                                                    |
| `PK`                      | Penalty kick goals scored in 2022 MLS season                                                                                                                                   |
| `PKatt`                   | Penalty kicks attempted in the 2022 MLS season                                                                                                                                 |
| `CrdY`                    | Number of yellow cards received in 2022 MLS season                                                                                                                             |
| `CrdR`                    | Number of red cards received in 2022 MLS season                                                                                                                                |
| `xG`                      | Expected number of goals in 2022 MLS season (basically prediction from another model)                                                                                          |
| `npxG`                    | Expected number of assists in 2022 MLS season                                                                                                                                  |
| `xAG`                     | Non-penalty expected goals in 2022 MLS season                                                                                                                                  |
| `PrgC`                    | Progressive carries by player in 2022 MLS season                                                                                                                               |
| `PrgP`                    | Progressive passes by player in 2022 MLS season                                                                                                                                |
| `PrgR`                    | Progressive passes received by player in 2022 MLS season                                                                                                                       |
| `Gls_pr90`                | Goals scored per 90 minutes in 2022 MLS season                                                                                                                                 |
| `Ast_pr90`                | Assists per 90 minutes in 2022 MLS season                                                                                                                                      |
| `xG_pr90`                 | Expected goals per 90 minutes in 2022 MLS season                                                                                                                               |
| `xAG_pr90`                | Expected assists per 90 minutes in 2022 MLS season                                                                                                                             |
| `npxG_pr90`               | Non-penalty expected goals per 90 minutes in 2022 MLS season                                                                                                                   |
| `team`                    | Player’s team                                                                                                                                                                  |
| `base_salary`             | Current annualized base salary in hundred thousands of dollars. Includes base salary and all signing and guaranteed bonuses annualized over the term of the player’s contract. |
| `guaranteed_compensation` | Annualized average guaranteed compensation in hundred thousands of dollars. Base salary plus marketing bonuses and any agent’s fees.                                           |

</div>
