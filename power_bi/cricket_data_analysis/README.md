# Cricket Data Analysis  

## Objective  
We aim to identify the best 11 cricket players in the world who:  
- Can score at least **180 runs on average**.  
- Can defend **150 runs on average**.  

## Selection Parameters  

### Openers  
| Parameter        | Description                        | Criteria   |
|------------------|------------------------------------|------------|
| Batting Average  | Average runs scored per innings    | > 30       |
| Strike Rate      | Runs scored per 100 balls          | > 140      |
| Innings Batted   | Total innings played               | > 3        |
| Boundary %       | Percentage of runs in boundaries   | > 50       |
| Batting Position | Order in the batting lineup        | < 4        |  

### Anchors / Middle Order  
| Parameter        | Description                        | Criteria   |
|------------------|------------------------------------|------------|
| Batting Average  | Average runs scored per innings    | > 40       |
| Strike Rate      | Runs scored per 100 balls          | > 125      |
| Innings Batted   | Total innings played               | > 3        |
| Avg. Balls Faced | Average balls faced per innings    | > 20       |
| Batting Position | Order in the batting lineup        | > 2        |  

### Finisher / Lower Order Anchor  
| Parameter        | Description                        | Criteria   |
|------------------|------------------------------------|------------|
| Batting Average  | Average runs scored per innings    | > 25       |
| Strike Rate      | Runs scored per 100 balls          | > 130      |
| Innings Batted   | Total innings played               | > 3        |
| Avg. Balls Faced | Average balls faced per innings    | > 12       |
| Batting Position | Order in the batting lineup        | > 4        |
| Innings Bowled   | Total innings bowled               | > 1        |  

### All-Rounders / Lower Order  
| Parameter           | Description                        | Criteria   |
|---------------------|------------------------------------|------------|
| Batting Average     | Average runs scored per innings    | > 15       |
| Strike Rate         | Runs scored per 100 balls          | > 140      |
| Innings Batted      | Total innings played               | > 2        |
| Batting Position    | Order in the batting lineup        | > 4        |
| Innings Bowled      | Total innings bowled               | > 2        |
| Bowling Economy     | Runs allowed per over              | < 7        |
| Bowling Strike Rate | Balls required to take a wicket    | < 20       |  

### Specialist Fast Bowlers  
| Parameter           | Description                        | Criteria   |
|---------------------|------------------------------------|------------|
| Innings Bowled      | Total innings bowled               | > 4        |
| Bowling Economy     | Runs allowed per over              | < 7        |
| Bowling Strike Rate | Balls required to take a wicket    | < 16       |
| Bowling Style       | Type of bowling                   | %Fast%     |
| Bowling Average     | Runs allowed per wicket            | < 20       |
| Dot Ball %          | Percentage of dot balls bowled     | > 40       |  

## Usage  
Evaluate players using these parameters to select a balanced team. Ensure the collective performance aligns with the scoring and defending benchmarks.  
