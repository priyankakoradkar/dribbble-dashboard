# Angular Custom Grid & Chart Application

This project demonstrates a responsive Angular application with a **custom-built grid** and **charts**, incorporating best practices for scalable enterprise development — without relying on third-party UI libraries like Bootstrap, Material, or Tailwind.

---

## 🚀 Features

### ✅ Grid Functionality
- Fully custom-built HTML/CSS/SCSS Grid (no external libraries)
- Dynamic grid column rendering based on API structure
- Local-only `Add`, `Update`, and `Delete` operations
- Confirmation popups for delete actions
- Responsive layout using **SCSS + Flexbox**
- No data persistence (data resets on refresh)

### ✅ API Integration
- API: `https://01.fy25ey01.64mb.io/`
- API fetches grid metadata (column headers, properties like alignment and colors)
- Open endpoint, but integration is structured as if for production
- Built using Angular's **HttpClient** with:
  - Centralized API service
  - Error handling and loading state management
  - Reusable data interfaces

### ✅ UI/UX
- Custom styling using **pure SCSS** (no inline styles, no design frameworks)
- SCSS inheritance and reusable mixins
- Mobile-friendly layout using Flexbox
- Chart support using `Highcharts`
- Detailed attention to:
  - Font sizing and spacing
  - Border-radius, hover effects
  - Color palette and gradient application

### ✅ Navigation
- Vertical sidebar with icons only (non-functional)
- Separate bottom section for profile/settings icons

### ✅ Loading State
- Custom loading spinner shown while data is being fetched
- Simulated API delay (2 seconds)

---

## 🧱 Technologies Used

- **Angular** (v14+)
- **SCSS** (no Tailwind, Bootstrap, Material)
- **Highcharts** for charts
- **RxJS** for reactive data handling
- **Angular HttpClient** for API calls
- No external grid libraries (e.g., no Syncfusion, FlexGrid, etc.)

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
