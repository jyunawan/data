# Premier League Contract Data

This folder contains Premier League Contract Data scraped from spotrac.


Header | Definition
---|---------
`Player` | Name of the player
`Pos` | Position of the player (Forward, Midfielder, Defender, Goalkeeper)
`Team Currently With` | Team the player signed with
`Age At Signing` | Age player was at the start of contract
`Start` | Year the contract started
`End` | Year the contract ends (For some reason this value is one year too early, e.g. 2029 means the contract actually ends in 2030)
`Yrs` | Length of the contract
`Value` | Total value of the contract (Salary over the length of the contract)
`AAV` | Average annual value (Annual salary)

Source: [TransferMarkt](https://www.transfermarkt.us/premier-league/transfers/wettbewerb/GB1)
