# Git Basic Tutorial

I like apples and grapes and oranges. Alfa 2 modification. Beta 2 változtatás.

And I like pears.

<table>
<tr>
<th>Alfa</th>
<th>Béta</th>
</tr>

<!-- Új sor -->
<tr><td><!-- Alfa -->

- Új repo létrehozása a Github-on
- Béta felvétele (Settings/Collaborators/Add collaborator)

</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->

...

</td><td><!-- Béta -->

...

</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->

- `fruits.txt` fájl 3. sorának szerkesztése
- `git add fruits.txt`
- `git commit -m"alfa 1. módosítás"`
- `fruits.txt` fájl 3. sorának szerkesztése
- `git add fruits.txt`
- `git commit -m"alfa 2. módosítás"`

</td><td><!-- Béta -->

- `fruits.txt` fájl 3. sorának szerkesztése
- `git add fruits.txt`
- `git commit -m"béta 1. módosítás"`
- `fruits.txt` fájl 3. sorának szerkesztése
- `git add fruits.txt`
- `git commit -m"béta 2. módosítás"`

</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->

- `git push`
- OK

</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->



</td><td><!-- Béta -->

- `git push`
- Rejected, mivel az origin előrébb van
- `git pull --rebase`
- Conflict 1.
- `git status`
- Konfliktus feloldása (VSCode segít, de gyakorlatilag a fájl szerkesztése)
- `git add fruits.txt`
- `git status`
- `git rebase --continue`
- Conflict 2.
- `git status`
- Konfliktus feloldása
- `git add fruits.txt`
- `git status`
- `git rebase --continue`
- `git push`

</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->

- `git pull --rebase`

</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->



</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->



</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->



</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->

<!-- Új sor -->
<tr><td><!-- Alfa -->



</td><td><!-- Béta -->



</td></tr>
<!-- Sor vége -->


  
</table>