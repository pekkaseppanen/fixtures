tietokantakaavio
Team (pk) id: Integer, name: String
Player (pk) id: Integer, (fk) team_id: Integer -> Team, lastname: String, firstname: String, playernumber: Integer
Match (pk) id: Integer, (fk) home_team_id: Integer -> Team, (fk) away_team_id: Integer -> Team, matchday: Date
User (pk) id: Integer, (fk) team_id: Integer -> Team, username: String, password: String
