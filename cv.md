# **Katsiaryna Ruziyeva**


## **Contacts**

  * **Location :** Vilnius, Lithuania
  * **Phone:** +370 6 937-23-20
  * **Email:** katsiarynaruziyeva@gmail.com
  * **GitGub:** [katsiarynaruziyeva](https://github.com/katsiarynaruziyeva)

## About me

  I’m passionate about what I do. I want to be a member of a team. I strongly believe that only a team can achieve a high results.

## Skills

  * HTML
  * CSS/SCSS
  * JavaScript
  * Git
  * React
  * Redux
  * TypeScript

## Code Example
```
function NewsCard({ newsCardDetails, type }: { newsCardDetails: NewsInterface; type?: NewsDataTypes }) {
  const { id, title, image, organization, excerpt, published_at } = newsCardDetails;

  const location = useLocation();

  const newsImage = image ? image : newsImageMock;

  const getFormattedData = (date: Date) => {
    return format(new Date(date), "dd MMM, yyyy 'в' hh:mm", {
      locale: ru,
    });
  };

  const getCategorySearchParams = (category: NewsDataTypes): string => {
    return '?' + new URLSearchParams({ category: category }).toString();
  };

```
## Experience

  Volunteer at the [Freeunion.online](https://freeunion.online/) project


## Education

  * **University:** 
  1. VITEBSK STATE ORDER OF PEOPLES’ FRIENDSHIP MEDICAL UNIVERSITY
  2. MITSO
  * **Courses :**
  1. TeachMreSkills
  2. Udemy (React+Redux - профессиональная разработка)
  3. Udemy (Полный курс по JavaScript+React с нуля дло результата)
  4. Udemy (React JS.Практический курс 2020(Хуки,Классы, Redux))

## English

B1 (keep improving)