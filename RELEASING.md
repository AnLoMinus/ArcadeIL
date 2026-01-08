# RELEASING

## תהליך הוצאת גרסה
1. עדכון `VERSION` לגרסה החדשה.
2. עדכון `CHANGELOG.md` עם רשימת השינויים.
3. יצירת תגית Git:
   ```bash
   git tag vX.Y.Z
   git push --tags
   ```
4. יצירת Release ב־GitHub עם תקציר השינויים.
