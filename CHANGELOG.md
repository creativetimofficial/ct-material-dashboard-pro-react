# Change Log

## [2.1.0] 2022-02-14

- TypeScript version of the product is available: [Material Dashboard 2 PRO React TS](https://www.creative-tim.com/product/material-dashboard-2-pro-react-ts)

### Bug fixing

- Add the color prop to the useMemo dependencies list
- Fix the non-nested route issue
- Momoized the context provider values
- Fix the conditionally used of useContext for MDPagination component
- Fix the import/no-anonymouse-default-export

### Major style changes

### Deleted components

- DefaultNavbarCategories (src/examples/Navbars/DefaultNavbar/DefaultNavbarCategories.js
- DefaultNavbarLink (src/examples/Navbars/DefaultNavbar/DefaultNavbarLink.js
- DefaultNavbarMenu (src/examples/Navbars/DefaultNavbar/DefaultNavbarMenu.js
- Menus (src/examples/Navbars/DefaultNavbar/Menus)

### Added components

- DefaultNavbarDropdown (src/examples/Navbars/DefaultNavbar/DefaultNavbarDropdown.js)

### Deleted dependencies

```
react-html-parser
```

### Added dependencies

```
html-react-parser
```

### Updated dependencies

```
  "@emotion/cache"                             11.4.0          ->          11.7.1
  "@emotion/react"                             11.4.1          ->          11.7.1
  "@emotion/styled"                            11.3.0          ->          11.6.0
  "@fullcalendar/daygrid"                      5.9.0           ->          5.10.0
  "@fullcalendar/interaction"                  5.9.0           ->          5.10.0
  "@fullcalendar/react"                        5.9.0           ->          5.10.0
  "@fullcalendar/timegrid"                     5.9.0           ->          5.10.0
  "@mui/icons-material"                        5.2.0           ->          5.4.1
  "@mui/material"                              5.2.0           ->          5.4.1
  "@mui/styled-engine"                         5.2.0           ->          5.4.1
  "@react-jvectormap/core"                     1.0.0-alpha.7   ->          1.0.1
  "@react-jvectormap/world"                    1.0.0-alpha.4   ->          1.0.0
  "@testing-library/jest-dom"                  5.11.4          ->          5.16.2
  "@testing-library/react"                     12.1.0          ->          12.1.2
  "@testing-library/user-event"                12.1.10         ->          13.5.0
  "chroma-js"                                  2.1.2           ->          2.4.2
  "prop-types"                                 15.7.2          ->          15.8.1
  "react-images-viewer"                        1.6.7           ->          1.7.1
  "react-router-dom"                           6.0.2           ->          6.2.1
  "react-scripts"                              4.0.3           ->          5.0.0
  "stylis"                                     4.0.10          ->          4.0.13
  "stylis-plugin-rtl"                          2.1.0           ->          2.1.1
  "web-vitals"                                 1.0.1           ->          2.1.4
  "yup"                                        0.32.9          ->          0.32.11
```

### Warning

## [2.0.0] 2021-12-07

### Bug fixing

### Major style changes

- Migration from Material-UI to MUI v5.
- Migration from JSS to `styled` api, emotion and `sx` prop.
- Product folders and files structured are updated: [README](https://github.com/creativetimofficial/ct-material-dashboard-pro-react/blob/main/README.md)
- New components are added
- New example blocks are added
- Components are Example Blocks are now totally customizable and reusable
- Product now uses the react context api for global configurations

### Deleted components

- Accordion
- Badge
- Card
- Clearfix
- CustomButtons
- CustomDropdown
- CustomInput
- CustomLinearProgress
- CustomTags
- CustomUpload
- FixedPlugin
- Footer
- Grid
- Heading
- InfoArea
- Intruction
- Navbars
- NavPills
- Pagination
- ReactTable
- Sidebar
- Snackbar
- Table
- Tasks
- Timeline
- Typography
- Wizard

### Added components

- MDAlert
- MDAvatar
- MDBadge
- MDBadgeDot
- MDBox
- MDButton
- MDDatePicker
- MDDropzone
- MDEditor
- MDInput
- MDPagination
- MDProgress
- MDSnackbar
- MDSocialButton
- MDTypography
- Breadcrumbs
- Calendar
- Cards
  - BlogCards
    - SimpleBlogCard
  - BookingCard
  - ControllerCard
  - InfoCards
    - DefaultInfoCard
    - MiniInfoCard
    - ProfileInfoCard
  - MasterCard
  - PricingCards
    - DefaultPricingCard
  - ProjectCards
    - ComplexProjectCard
    - DefaultProjectCard
  - StatisticsCards
    - ComplexStatisticsCard
    - DefaultStatisticsCard
    - MiniStatisticsCard
- Charts
  - BarCharts
    - HorizontalBarChart
    - VerticalBarChart
    - ReportsBarChart
  - BubbleChart
  - DoughnutCharts
    - DefaultDoughnutChart
  - LineCharts
    - DefaultLineChart
    - GradientLineChart
    - ProgressLineChart
    - ReportsLineChart
  - MixedChart
  - PieChart
  - PolarChart
  - RadarChart
- Configurator
- Footer
- Items
  - DefaultItem
  - NotificationItem
- LayoutContainers
  - DashboardLayout
  - PageLayout
- Lists
  - CategoriesList
  - ProfilesList
- Navbars
  - DashboardNavbar
  - DefaultNavbar
- Sidenav
- Tables
  - DataTable
  - SalesTable
- Timeline
  - TimelineList
  - TimelineItem

### Deleted dependencies

```
@material-ui/core
@material-ui/icons
chartist
classnames
match-sorter
moment
node-sass
nouislider
perfect-scrollbar
react-big-calendar
react-bootstrap-sweetalert
react-chartist
react-datetime
react-jvectormap
react-swipeable-views
react-tagsinput
```

### Added dependencies

```
@mui/material
@mui/icons-material
@mui/styled-engine
@asseinfo/react-kanban
@emotion/cache
@emotion/react
@emotion/styled
@fullcalendar/daygrid
@fullcalendar/interaction
@fullcalendar/react
@fullcalendar/timegrid
@react-jvectormap/core
@react-jvectormap/world
@testing-library/jest-dom
@testing-library/react":
@testing-library/user-event
chart.js
chroma-js
dropzone
flatpickr
formik
prop-types
react-chartjs-2
react-flatpickr
react-html-parser
react-images-viewer
react-quill
stylis
stylis-plugin-rtl
uuid
web-vitals
yup
```

### Updated dependencies

### Warning

## [1.11.0] 2021-09-10

### Bug fixing

### Major style changes

### Deleted components

### Added components

### Deleted dependencies

### Added dependencies

### Updated dependencies

```
@material-ui/core        4.11.4   →   4.12.3
chartist                 0.10.1   →   0.11.4
node-sass                 5.0.0   →    6.0.1
nouislider               15.0.0   →   15.4.0
perfect-scrollbar         1.5.1   →    1.5.2
react-big-calendar       0.33.2   →   0.35.0
react-datetime            3.0.4   →    3.1.1
react-router-dom          5.2.0   →    5.3.0
react-swipeable-views    0.13.9   →   0.14.0
eslint-plugin-prettier    3.4.0   →    4.0.0
prettier                  2.2.1   →    2.4.0
@babel/core              7.14.0   →   7.15.5
typescript                4.2.4   →    4.4.2
```

### Warning

_The following warnings will appear when running the installation command, but they do not affect the UI or the functionality of the product (they will be solved in our next update):_

```
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated har-validator@5.1.5: this library is no longer supported
npm WARN react-event-listener@0.6.6 requires a peer of react@^16.3.0 but none is installed. You must install peer dependencies yourself.
```

_If they will persist in our 2.*.* version, we will drop their usages and replace them with other plugins._
_In development mode, some of the above plugins will throw a warning because they still use React v16 syntax. If the error will persist in our 2.*.* version, we will drop their usage and replace them with other plugins._

**Note:** There are 6 vulnerabilities when running the `npm install` command, to fix it just run the following command `npm audit fix` once the installation is finished.

## [1.10.0] 2021-05-10

### Bug fixing

- Changed Multi Level Collapse links and layouts to stop it opening when going to the /admin/buttons page
- Change SidebarWrapper from class to function component
- Change Sidebar from class to function component
  - Also, made the Multi Level Collapse stop opening when navigating to /admin/buttons
  - Also, made the collapses close when opening a new one
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/253
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/252
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/251
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/243
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/232
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/229
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/228
- Change Step1, Step2 and Step3 of Wizard component from class components to functional ones
  - NOTE: The Wizard still accepts class components as well
  - NOTE: The Wizard is still a class component. It could not be changed to functional component as of the moment :(. We will continue to find a solution for this component as well.

### Major style changes

### Deleted components

### Added components

### Deleted dependencies

- `react-google-maps` (we've replaced this with simple Google Maps API)
- `@types/googlemaps` (we've replaced this with simple Google Maps API)
- `@types/markerclustererplus` (we've replaced this with simple Google Maps API)
- `ajv` (this was only installed to stop some install warnings)
- `history` (we'll use `BrowserRouter` from `react-router-dom` package instead)

### Added dependencies

- `@babel/core@7.14.0 `(to stop warnings)

### Updated dependencies

```
@material-ui/core             4.9.14   →   4.11.4
@material-ui/icons             4.9.1   →   4.11.2
classnames                     2.2.6   →    2.3.1
match-sorter                   4.1.0   →    6.3.0
moment                        2.26.0   →   2.29.1
node-sass                     4.14.1   →    5.0.0
nouislider                    14.5.0   →   15.0.0
perfect-scrollbar              1.5.0   →    1.5.1
react                        16.13.1   →   17.0.2
react-big-calendar            0.24.6   →   0.33.2
react-bootstrap-sweetalert     5.1.9   →    5.2.0
react-chartist                0.14.3   →   0.14.4
react-datetime                2.16.3   →    3.0.4
react-dom                    16.13.1   →   17.0.2
react-scripts                  3.4.1   →    4.0.3
react-table                    7.1.0   →    7.7.0
eslint-config-prettier        6.11.0   →    8.3.0
eslint-plugin-prettier         3.1.3   →    3.4.0
gulp-append-prepend            1.0.8   →    1.0.9
prettier                       2.0.5   →    2.2.1
typescript                     3.9.3   →    4.2.4
```

### Warning

_In the next version, we'll change all the ReactTable components to JSS based components, the same these tables were created: https://demos.creative-tim.com/material-dashboard-pro-react/#/admin/extended-tables or these https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/table_
_While in development some of the plugins that were used for this product will throw some warnings - note, this only happens in development, the UI or the functionality of the product is not affected, also, if the issues will persist in React 17, we'll drop usage of those plugins, and replace them with other ones._
_Warnings might appear while doing an npm install - they do not affect the UI or the functionality of the product, and they appear because of NodeJS and not from the product itself._

```
npm WARN react-datetime@3.0.4 requires a peer of react@^16.5.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-event-listener@0.6.6 requires a peer of react@^16.3.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-swipeable-views@0.13.9 requires a peer of react@^15.3.0 || ^16.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-tagsinput@3.19.0 requires a peer of react@^16.0.0 || ^15.0.0 || ^0.14.0 but none is installed. You must install peer dependencies yourself.
```

_You will also have the following message: `found 1 low severity vulnerability`. This comes from `gulp`, and will be fixed in the next version. NOTE: the product works as expected with these `vulnerabilities`._

## [1.9.0] 27.05.2020

### Bug fixing

- Add `React.useEffect` inside `src/views/Pages/LoginPage.js` and `src/views/Pages/LockScreenPage.js` so that the `setTimeout` will not throw errors on route change
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/219 (added two new props for this component, so you can easily use your own default value and your own function for changing this value)
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/214
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/212
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/208
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/195
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/194
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/225
- From other repositories:
  - https://github.com/creativetimofficial/ct-material-kit-pro-react/issues/60

### Major style changes

- `src/assets/jss/material-dashboard-pro-react/layouts/authStyle.js`
- `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-react-bootstrap-sweetalert.scss`
- `src/assets/jss/material-dashboard-pro-react/components/sidebarStyle.js`
- `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-react-table.scss`

### Deleted components

### Added components

- `src/components/CustomTabs/CustomTabs.js` (This was because of the update to React-Table 7 API. NOTE: this is just a demo component to showcase the usage of the API, if you wish to add more functionality from the API, you should either duplicate the component, or work over it.)

### Deleted dependencies

### Added dependencies

- classnames@2.2.6
- match-sorter@4.1.0

### Updated dependencies

```
@material-ui/core             4.3.2   →    4.9.14
@material-ui/icons            4.2.1   →     4.9.1
history                       4.9.0   →    4.10.1
moment                       2.24.0   →    2.26.0
node-sass                    4.12.0   →    4.14.1
nouislider                   14.0.2   →    14.5.0
perfect-scrollbar             1.4.0   →     1.5.0
react                        16.9.0   →   16.13.1
react-big-calendar           0.22.0   →    0.24.6
react-bootstrap-sweetalert    4.4.1   →     5.1.9
react-chartist               0.13.3   →    0.14.3
react-dom                    16.9.0   →   16.13.1
react-jvectormap             0.0.12   →    0.0.16
react-router-dom              5.0.1   →     5.2.0
react-scripts                 3.1.0   →     3.4.1
react-swipeable-views        0.13.3   →    0.13.9
react-table                  6.10.0   →     7.1.0
eslint-config-prettier        6.0.0   →    6.11.0
eslint-plugin-prettier        3.1.0   →     3.1.3
prettier                     1.18.2   →     2.0.5
@types/googlemaps            3.37.3   →    3.39.6
ajv                          6.10.2   →    6.12.2
typescript                    3.5.3   →     3.9.3
```

### Warning

_In the next version, we'll change all the ReactTable components to JSS based components, the same these tables were created: https://demos.creative-tim.com/material-dashboard-pro-react/#/admin/extended-tables or these https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/table_
_While in development some of the plugins that were used for this product will throw some warnings - note, this only happens in development, the UI or the functionality of the product is not affected, also, if the issues will persist in React 17, we'll drop usage of those plugins, and replace them with other ones._
_Warnings might appear while doing an npm install - they do not affect the UI or the functionality of the product, and they appear because of NodeJS and not from the product itself._

## [1.8.0] 2019-08-26

### Warning

- Wizard and Wizard Steps were not changed to hooks since we need to be able to call the isValidated function (this can only be achieved with classes - withStyles function is still being used)
- Sidebar Component could not be changed to hooks due to the dynamic nature of this component (the collapses states are done dynamically, and you do not have anyway of knowing the amount of collapses this component will have to create static states - withStyles function is still being used)

### Bug fixing

- Rewrote the ISSUE_TEMPLATE
- Deleted the copyright comments from all files, we only need to keep them inside our index.js and index.html
- Added script that adds copyrights to the built app
- Renamed all the files from `.jsx` to `.js`
- Changed the `withStyles` function from Material-UI with the `makeStyles` function (integration with other frameworks should now be easy)
- React Hooks is now supported (Please read the above warnings)

### Major style changes

- `src/assets/jss/material-dashboard-pro-react/components/customDropdownStyle.js`
- `src/assets/jss/material-kit-pro-react/components/cardBodyStyle.js`
- `src/assets/scss/plugins/_plugin-nouislider.scss`

### Deleted components

### Added components

### Deleted dependencies

### Added dependencies

- gulp@4.0.2
- gulp-append-prepend@1.0.8

### Updated dependencies

```
@material-ui/core         4.1.0   →    4.3.2
@material-ui/icons        4.1.0   →    4.2.1
nouislider               13.1.5   →   14.0.2
react                    16.8.6   →   16.9.0
react-big-calendar       0.21.0   →   0.22.0
react-dom                16.8.6   →   16.9.0
react-scripts             3.0.1   →    3.1.0
eslint-config-prettier    4.3.0   →    6.0.0
@types/googlemaps        3.36.4   →   3.37.3
ajv                      6.10.0   →   6.10.2
typescript                3.5.1   →    3.5.3
```

## [1.7.0] 2019-06-19

### Warning

**We've skipped version 1.6.0 so that all React Material products would be on the same version.**

### Bug fixing

- Bugs from updated dependencies
- Removed `.env` file, and replaced it with the `jsconfig.json` file
- Changes caused by running [the prettier command](https://prettier.io/docs/en/install.html) for _.jsx_, _.js_, _.html_ and _.css_ files
- Changed all string refs to `React.createRef()`
- Added types validation in each component
- Solved linting issues
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/149
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/161
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/171
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/172
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/176
- Solved https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/177

### Major style changes

### Deleted components

### Added components

### Deleted dependencies

### Added dependencies

- typescript@3.5.1 (To stop console warnings on install)
- eslint-plugin-react@7.13.0
- eslint@5.16.0

### Updated dependencies

```
@material-ui/core          3.9.2   →    4.1.0
@material-ui/icons         3.0.2   →    4.1.0
history                    4.7.2   →    4.9.0
node-sass                 4.11.0   →   4.12.0
nouislider                13.1.0   →   13.1.5
react                     16.8.1   →   16.8.6
react-big-calendar        0.20.3   →   0.21.0
react-dom                 16.8.1   →   16.8.6
react-jvectormap           0.0.6   →   0.0.12
react-router-dom           4.3.1   →    5.0.1
react-scripts              2.1.5   →    3.0.1
react-swipeable-views     0.13.1   →   0.13.3
react-table                6.9.2   →   6.10.0
eslint-config-prettier     4.0.0   →    4.3.0
eslint-plugin-prettier     3.0.1   →    3.1.0
@types/googlemaps        3.30.16   →   3.36.4
ajv                        6.9.1   →   6.10.0
prettier                  1.16.4   →   1.18.2
```

## [1.5.0] 2019-02-13

### Bug Fixing

- Deleted some unnecessary scripts (See available scripts here: https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/build-tools)
- Changed our buggy routing system, now it should work flawlessly, for more info, please refer to our [live docs here](https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/routing-system)
- Changes caused by running [the prettier command](https://prettier.io/docs/en/install.html) for _.jsx_, _.js_, _.html_ and _.css_ files
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/137
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/132
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/128
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/88
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/87
- https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/85

### Major style changes

- Changes caused by the fact that all colors are now variables and the prettier command

### Dropped components

- `src/layouts/Dashboard.jsx`, now it is called `src/layouts/Admin.jsx`
- `src/layouts/Pages.jsx`, now it is called `src/layouts/Auth.jsx`
- `src/components/Header/Header.jsx`, now it is called `src/components/Navbars/AdminNavbar.jsx`
- `src/components/Header/HeaderLinks.jsx`, now it is called `src/components/Navbars/AdminNavbarLinks.jsx`
- `src/components/Header/PagesHeader.jsx`, now it is called `src/components/Navbars/AuthNavbar.jsx` (This has no longer dynamic links)
- `assets/jss/material-dashboard-pro-react/components/pagesHeaderStyle.jsx`, now it is called `assets/jss/material-dashboard-pro-react/components/authNavbarStyle.jsx`
- `assets/jss/material-dashboard-pro-react/components/headerStyle.jsx`, now it is called `assets/jss/material-dashboard-pro-react/components/adminNavbarStyle.jsx`
- `assets/jss/material-dashboard-pro-react/components/headerLinksStyle.jsx`, now it is called `assets/jss/material-dashboard-pro-react/components/adminNavbarLinksStyle.jsx`

### Added components

- Added new view component for 404 pages (`src/views/Pages/ErrorPage.jsx`)

### Deleted dependencies

- `node-sass-chokidar`
- `npm-run-all`
- `eslint-plugin-react`
- `eslint`
- `babel-eslint`
- `@babel/core`

### Added dependencies

- `node-sass` version: **4.11.0**

### Updated dependencies

- `@material-ui/core` _3.1.1_ → **3.9.1**
- `@material-ui/icons` _3.0.1_ → **3.0.2**
- `moment` _2.22.2_ → **2.24.0**
- `nouislider` _12.0.0_ → **13.1.0**
- `perfect-scrollbar` _1.4.0_ → **1.4.4**
- `react` _16.5.2_ → **16.8.1**
- `react-big-calendar` _0.20.1_ → **0.20.3**
- `react-chartist` _0.13.1_ → **0.13.3**
- `react-datetime` _2.15.0_ → **2.16.3**
- `react-dom` _16.5.2_ → **16.8.1**
- `react-jvectormap` _0.0.3_ → **0.0.6**
- `react-scripts` _1.1.5_ → **2.1.5**
- `react-swipeable-views` _0.13.0_ → **0.13.1**
- `react-table` _6.8.6_ → **6.9.2**
- `@types/googlemaps` _3.30.13_ → **3.30.16**
- `ajv` _5.0.0_ → **6.9.1**
- `eslint-config-prettier` _3.1.0_ → **4.0.0**
- `eslint-plugin-prettier` _2.6.2_ → **3.0.1**
- `prettier` _1.14.3_ → **1.16.4**

## [1.4.0] 2018-09-29

### Styles changed

- `src/assets/jss/material-dashboard-pro-react/components/customDropdownStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/components/customInputStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/components/customTabsStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/components/snackbarContentStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/components/tasksStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/layouts/pagesStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/views/extendedFormsStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/views/validationFormsStyle.jsx`
- `src/assets/jss/material-dashboard-pro-react/customCheckboxRadioSwitch.jsx`
- `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-nouislider.scss`
- `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-react-big-calendar.scss`

### Bug Fixing

- Run `prettier` (minor code writting bugs)
- Added `npm run node_modules` (**Mac/Linux**) and `npm run node_modules-w` (**Windows**) scripts (deletes `node_modules` and `package-lock.json`)
- Added `npm run install:clean` (**Mac/Linux**) and `npm run install:clean-w` (**Windows**) scripts (deletes `node_modules` and `package-lock.json`, runs `npm install` and runs `npm start`)
- Github own issues solved:
  - [https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/79](https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/79)
  - [https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/66](https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/66)
- Github other issues solved:
  - [https://github.com/creativetimofficial/material-kit-react/issues/36](https://github.com/creativetimofficial/material-kit-react/issues/36)

### Deleted dependencies

- `@babel/runtime`
- `react-nouislider` (since it was not well maintained)

### Added dependencies

- `@babel/core` `7.0.0`
- `nouislider` `12.0.0` (instead of `react-nouislider`)

### Updated dependencies

- `@material-ui/core` `1.4.3` → `3.1.1`
- `@material-ui/icons` `2.0.1` → `3.0.1`
- `@types/googlemaps` `3.30.11` → `3.30.13`
- `ajv` `6.5.2` → `5.0.0`
- `react` `16.4.1` → `16.5.2`
- `react-big-calendar` `0.19.2` → `0.20.1`
- `react-dom` `16.4.1` → `16.5.2`
- `react-scripts` `1.1.4` → `1.1.5`
- `react-swipeable-views` `0.12.15` → `0.13.0`
- `eslint-config-prettier` `^2.9.0` → `3.1.0`
- `eslint-plugin-react` `^7.10.0` → `7.11.1`
- `prettier` `^1.13.7` → `1.14.3`

## [1.3.0] 2018-08-09

### Major style changes

- Added styles for `svg`'s, **font-awesome** classes and `.material-icons` class inside
  - `src/assets/jss/material-dashboard-pro-react/views/dashboardStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/extendedTablesStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/pricingPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/buttonStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/cardFooterStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/cardHeaderStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/cardStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/customInputStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/customTabsStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/headerLinksStyle.jsx`
- Others
  - `src/assets/jss/material-dashboard-pro-react/views/regularFormsStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/customInputStyle.jsx`
  - `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-react-big-calendar.scss`
  - `src/assets/jss/material-dashboard-pro-react/layouts/pagesStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/registerPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/loginPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/pricingPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/lockScreenPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/customDropdownStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/customSelectStyle.jsx` (added some special class for the multiple select)

### Bug Fixing

- Run `prettier` (minor code writting bugs)
- Added lint commands (please read the live docs)
- Added back the `helpText` prop on `CustomInput` component (if the `CustomInput` has the `error` prop set, the `helpText` wil have error color, if the `success` prop is set on `CustomInput` then the `helpText` will have success color)
- Deleted the `Clear` (icon that appeared on `error` for `CustomInput`) and `Check` (icon that appeared on `success` for `CustomInput`) - now you should use `InputAdornment` from `@material-ui/core`
- Changed `CustomDropdown`, now it uses `@material-ui/core/Popper`, instead of `{ Manager, Target, Popper }` from `react-popper`
- Changed the dropdown link in `HeaderLinks`, now it uses `@material-ui/core/Popper`, instead of `{ Manager, Target, Popper }` from `react-popper`
- Github issues solved:
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/34`
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/35`
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/39`
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/40`
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/54` (added docs for this issue)
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/55`
  - `https://github.com/creativetimofficial/ct-material-dashboard-pro-react/issues/62`

### Deleted dependencies

### Added dependencies

- `@babel/runtime v7.0.0-beta.55`

### Updated dependencies

- `@material-ui/core v1.2.0` to `@material-ui/core v1.4.3`
- `@material-ui/icons v1.1.0` to `@material-ui/icons v2.0.1`
- `@types/googlemaps v3.30.8` to `@types/googlemaps v3.30.11`
- `ajv v6.5.0` to `ajv v6.5.2`
- `moment v2.22.1` to `moment v2.22.2`
- `node-sass-chokidar v1.3.0` to `node-sass-chokidar v1.3.3`
- `perfect-scrollbar v1.3.0` to `perfect-scrollbar v1.4.0`
- `react v16.4.0` tp `react v16.4.1`
- `react-big-calendar v0.19.1` to `react-big-calendar v0.19.2`
- `react-datetime v2.14.0` to `react-datetime v2.15.0`
- `react-dom v16.4.0` to `react-dom 16.4.1`
- `react-router-dom v4.2.2` to `react-router-dom v4.3.1`
- `react-swipeable-views v0.12.13` to `react-swipeable-views v0.12.15`

## [1.2.0] 2018-06-08

### **IMPORTANT!!!**

- All cards have been changed
- Please take a look in our [documentation about cards](https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/cards) and see how to make these changes

### Breaking changes

- Some props have been dropped, and some props have been added instead (please read our [live docs](https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/tutorial))
- Instead of using Material-UI's Cards, which are the base of our Cards in material-dashboard-pro-react@v1.1.1 and prior, we've decided to start from scratch and create our own components for the Cards
- All `*NoBackground` colors of the custom Button have been dropped, and have been replaced by adding the properties `simple color="*"` (where `*` is one of `info`, `danger` etc.)
- Dropped components
  - CustomButton
    - **`IconButton.jsx`** (instead of this one - use `Button` with `justIcon` prop)
  - Cards
    - **`ChartCard.jsx`**
    - **`PricingCard.jsx`**
    - **`FullHeaderCard.jsx`**
    - **`ProfileCard.jsx`**
    - **`HeaderCard.jsx`**
    - **`RegularCard.jsx`**
    - **`IconCard.jsx`**
    - **`StatsCard.jsx`**
    - **`ImagePriceCard.jsx`**
    - **`TasksCard.jsx`**
    - **`LoginCard.jsx`**
    - **`TestimonialCard.jsx`**
  - Grid
    - **`ItemGrid.jsx`**
- Added components
  - Cards (these are the replacement of the above deleted **Cards**)
    - **`Card.jsx`**
    - **`CardBody.jsx`**
    - **`CardHeader.jsx`**
    - **`CardFooter.jsx`**
    - **`CardIcon.jsx`**
  - **`CustomTabs/CustomTabs.jsx`** instead part of **`TasksCard.jsx`**
  - Grid
    - **`GridItem.jsx`** instead of the above deleted **Grid**
- Renamed the `*cardHeader` variables
  - from
    - `orangeCardHeader`
    - `greenCardHeader`
    - `redCardHeader`
    - `blueCardHeader`
    - `purpleCardHeader`
  - to
    - `warningCardHeader`
    - `successCardHeader`
    - `dangerCardHeader`
    - `infoCardHeader`
    - `primaryCardHeader`
- Changed the way we render `Switch`, `Select` and `Checkbox` (on Wizard page - Step2 - `IconCheckboxes`) components
- Changed the `ImageUpload` components - they weren't rendering correctly on apple products
- Major style changes:
  - `src/assets/jss/material-dashboard-pro-react/components/accordionStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/buttonStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/customInputStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/headerLinksStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/headerStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/navPillsStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/components/tasksStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/extendedTablesStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/notificationsStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/registerPageStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/userProfileStyles.jsx`
  - `src/assets/jss/material-dashboard-pro-react/views/validationFormsStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/customCheckboxRadioSwitch.jsx`
  - `src/assets/jss/material-dashboard-pro-react/customSelectStyle.jsx`
  - `src/assets/jss/material-dashboard-pro-react/modalStyle.jsx`
  - `src/assets/scss/material-dashboard-pro-react/plugins/_plugin-react-big-calendar.scss`
  - `src/assets/jss/material-dashboard-pro-react/components/customDropdownStyle.jsx`
  - `src/assets/scss/material-dashboard-pro-react/_fileupload.scss`

### Bug Fixing

- Due to the change of material-ui, all the imports from this library have been changed
- Added props on the `Wizard` component and **Wizard Steps** components so that you can pass states between them ([please read the docs](https://demos.creative-tim.com/material-dashboard-pro-react/#/documentation/wizard))
- Used prettier to make the code more readable
- Added `/*eslint-disable*/` at the start of some files to stop showing warnings about links

### Deleted dependencies

- `material-ui@1.0.0-beta.41`

### Added dependencies

- `@material-ui/core@1.2.0` (instead of `material-ui@1.0.0-beta.41`)
- `ajv@6.5.0` to stop the warning `npm **WARN** ajv-keywords@3.2.0 requires a peer of ajv@^6.0.0 but none is installed. You must install peer dependencies yourself.`
- `@types/markerclustererplus@2.1.33` to stop the warning `npm **WARN** react-google-maps@9.4.5 requires a peer of @types/markerclustererplus@^2.1.29 but none is installed. You must install peer dependencies yourself.`
- `@types/googlemaps@3.30.8` to stop the warning `npm **WARN** react-google-maps@9.4.5 requires a peer of @types/googlemaps@^3.0.0 but none is installed. You must install peer dependencies yourself.`

### Updated dependencies

- `@material-ui/icons@1.0.0-beta.42` to `@material-ui/icons@1.1.0`
- `node-sass-chokidar@1.2.2` to `node-sass-chokidar@1.3.0`
- `npm-run-all@4.1.2` to `npm-run-all@4.1.3`
- `react@16.2.0` to `react@16.4.0`
- `react-big-calendar@0.18.0` to `react-big-calendar@0.19.1`
- `react-bootstrap-sweetalert@4.2.3` to `react-bootstrap-sweetalert@4.4.1`
- `react-dom@16.2.0` to `react-dom@16.4.0`
- `react-jvectormap@0.0.2` to `react-jvectormap@0.0.3`
- `react-table@6.8.0` to `react-table@6.8.6`

## [1.1.1] 2018-05-22

### Bug Fixing

- Changed links for live preview, online documentation and issues
- Changed links from `http` to `https`

## [1.1.0] 2018-04-16

### Bug Fixing

- Changes caused by the upgrade of `material-ui`

### Deleted dependencies

- `material-ui-icons@1.0.0-beta.36`

### Added dependencies

- `@material-ui/icons@1.0.0-beta.42` (instead of `material-ui-icons@1.0.0-beta.36`)

### Updated dependencies

- `material-ui@1.0.0-beta.34` to `material-ui@1.0.0-beta.41`
- `npm-run-all@4.1.1` to `npm-run-all@4.1.2`
- `react-scripts@1.1.1` to `react-scripts@1.1.4`
- `node-sass-chokidar@0.0.3` to `node-sass-chokidar@1.2.2`
- `moment@2.21.0` to `moment@2.22.1`

## [1.0.0] 2018-03-27

### Original Release

- Added Material-UI as base framework
- Added design from Material Dashboard Pro BS3 by Creative Tim
