# amara-bakes-site

Website content for **Amara Bakes**, a fictional bakery with four branches (Ikeja, Lekki, Yaba, Surulere).
The "Find a branch" page reads its opening hours from `data/hours.json`.

## Updating branch hours

1. Hours come only from the **Branch Hours Update** Google Form, through its linked results sheet.
2. Use **24-hour time** in the format `HH:MM-HH:MM`, for example `07:00-19:00`.
3. Change only the branches that are approved to publish. Leave every other branch exactly as it is.
4. Set `"updated"` to the date you make the change, in the format `YYYY-MM-DD`.
5. Commit straight to `main` with a message that starts with `Update hours:` and lists the branches you changed.
