# Grand-Tournament-of-the-Seven-Kingdoms

In the Seven Kingdoms, a grand tourney is held where Knights battle to conquer territories and earn honor. The laws of the tourney are as follows:

Whenever a Knight conquers a territory, they earn 1 honor point.
The first knight to conquer a particular territory earns 1 additional honor point.
There are 26 territories, each marked by a sigil from A to Z.
No knight may conquer the same territory again.
Some territories may remain unconquered by the end of the tourney.

You are given a record of the battles fought, written as a string. Each character represents the sigil of a territory conquered at that moment. Your task is to calculate the total honor points earned by all knights during the tourney.

Input
Single line contains a string s consisting of uppercase English letters (A to Z), denoting the order of conquered territories.
Output
Print a single integer — the total honor points earned by all knights.
Constraints
1 ≤ len(s) ≤ 50
s consists only of uppercase English letters (A to Z)

code:-

s = input().strip()

distinct = len(set(s))
total_points = len(s) + distinct

print(total_points)
