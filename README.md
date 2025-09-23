
## React TypeScript + Ant Design Snippets

Bộ snippets hoàn chỉnh cho React TypeScript với Ant Design, tập trung vào các thao tác CRUD và components thường dùng.


## 📋 Danh sách Snippets

### 🔧 CRUD Operations (Core)

| Prefix | Mô tả |
|--------|--------|
| `crudlist` | Complete CRUD List với Modal inline |
| `cruddetail` | Detail View component với routing |
| `crudform` | Create/Edit Form component với routing |
| `crudsearch` | Search/Filter component |
| `crudservice` | Custom Hook cho API calls |
| `crudpage` | Complete CRUD Page (All-in-one) |

### 📝 Form Components

| Prefix | Mô tả |
|--------|--------|
| `antform` | Form cơ bản với TypeScript |
| `finput` | Form Item với Input |
| `fselect` | Form Item với Select |
| `ftextarea` | Form Item với TextArea |
| `fswitch` | Form Item với Switch |
| `fcheckbox` | Form Item với Checkbox |
| `fradio` | Form Item với Radio Group |
| `fupload` | Form Item với Upload |
| `fdatepicker` | Form Item với DatePicker |
| `frangepicker` | Form Item với RangePicker |
| `finputnumber` | Form Item với InputNumber |
| `fpassword` | Form Item với Password Input |
| `sopt` | Select Option |
| `useform` | useForm hook |

###  Table Components

| Prefix | Mô tả |
|--------|--------|
| `anttable` | Table cơ bản với TypeScript |
| `tcol` | Table Column cơ bản |
| `tcoladvanced` | Advanced Column với filters & render |
| `taction` | Action Column với Edit/Delete |
| `tcolstatus` | Status Column với Tags |
| `tcoldate` | Date formatting Column |
| `tcolimage` | Image display Column |

###  UI Components

| Prefix | Mô tả |
|--------|--------|
| `antmodal` | Modal component |
| `antdrawer` | Drawer component |
| `antsteps` | Steps component |
| `antupload` | Upload component |
| `anttabs` | Tabs component |
| `antlayout` | Layout với Sidebar |
| `btn` | Button với variants |
| `card` | Card component |
| `breadcrumb` | Breadcrumb navigation |
| `pagination` | Pagination component |
| `spin` | Loading Spinner |

###  Feedback Components

| Prefix | Mô tả |
|--------|--------|
| `notify` | Notification |
| `msg` | Message |
| `popconfirm` | Popconfirm |
| `tooltip` | Tooltip |
| `confirmmodal` | Confirmation Modal |

###  Utility Functions

| Prefix | Mô tả |
|--------|--------|
| `apierror` | API Error Handler |
| `useloading` | Loading State Hook |

###  Navigation

| Prefix | Mô tả |
|--------|--------|
| `mitem` | Menu Item |
| `tabitem` | Tab Item |

###  Date Components

| Prefix | Mô tả |
|--------|--------|
| `datepicker` | DatePicker standalone |
| `rangepicker` | RangePicker standalone |

##  Ví dụ sử dụng

### 1. Tạo CRUD Page hoàn chỉnh
```typescript
// Gõ: crudpage + Tab
// Sẽ generate một trang CRUD hoàn chỉnh với:
// - Search/Filter
// - Table với pagination
// - Modal Create/Edit/View
// - Delete confirmation
```

### 2. Tạo Form đơn giản
```typescript
// Gõ: antform + Tab
// Sau đó thêm các field:
// finput + Tab (Input field)
// fselect + Tab (Select field)
// fdatepicker + Tab (Date picker)
```

### 3. Tạo Table với actions
```typescript
// Gõ: anttable + Tab
// Thêm columns:
// tcol + Tab (Basic column)
// tcolstatus + Tab (Status column với tags)
// taction + Tab (Action column với Edit/Delete)
```

### 4. Sử dụng Service Hook
```typescript
// Gõ: crudservice + Tab
// Tạo custom hook với các method:
// - getList, getById, create, update, remove
// - Built-in error handling và loading states
```

##  Cấu hình TypeScript

Đảm bảo project có các dependencies sau:

```json
{
  "dependencies": {
    "react": "^18.0.0",
    "antd": "^5.0.0",
    "react-router-dom": "^6.0.0"
  },
  "devDependencies": {
    "typescript": "^5.0.0",
    "@types/react": "^18.0.0",
    "@types/react-dom": "^18.0.0"
  }
}
```

##  Best Practices

### 1. Interface Naming
- Sử dụng `DataType` cho entity interfaces
- Sử dụng `FormData` cho form interfaces  
- Sử dụng `SearchFilters` cho search interfaces

### 2. API Endpoints
- Tuân theo RESTful convention:
  - `GET /api/users` - List
  - `GET /api/users/:id` - Detail
  - `POST /api/users` - Create
  - `PUT /api/users/:id` - Update
  - `DELETE /api/users/:id` - Delete

### 3. Error Handling
- Sử dụng `apierror` snippet cho consistent error handling
- Hiển thị user-friendly messages
- Log errors cho debugging

### 4. Loading States
- Sử dụng `useloading` hook cho loading management
- Show loading indicators cho better UX
- Disable actions khi đang loading


## 📚 Resources

- [Ant Design Documentation](https://ant.design/docs/react/introduce)
- [React TypeScript Cheatsheet](https://react-typescript-cheatsheet.netlify.app/)
- [VS Code Snippets Guide](https://code.visualstudio.com/docs/editor/userdefinedsnippets)


##  License

MIT License - sử dụng tự do cho mọi dự án!

---

**Happy Coding!**

*Tạo ứng dụng React + Antd nhanh hơn với bộ snippets này!*