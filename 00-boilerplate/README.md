# پروژه نمونه تایپ‌اسکریپت گام آزمون

یک پروژه نمونه و حداقلی برای شروع برنامه‌نویسی با Node.js و TypeScript، به عنوان بخشی از پلتفرم آموزشی گامازمون.

## ویژگی‌ها

- **تایپ‌اسکریپت**: استفاده از آخرین ویژگی‌های ECMAScript و امنیت نوع (type safety).
- **tsx**: برای اجرای مستقیم کدهای تایپ‌اسکریپت در حالت توسعه (با `tsx watch` برای بارگذاری مجدد خودکار).
- **ساخت (Build)**: کامپایل کدهای تایپ‌اسکریپت به جاوااسکریپت.

## نصب و راه‌اندازی

۱. مخزن (repository) را کلون کنید:

   ```bash
   git clone https://github.com/gamazmoon/typescript.git
   cd typescript
   ```

۲. وابستگی‌ها را نصب کنید:
   ```bash
   npm install
   ```

## دستورات (Scripts)

 - **Build**: کامپایل کردن کدهای تایپ‌اسکریپت به جاوااسکریپت
  ```bash
  npm run build
  ```

- **Start**: Run the compiled application

  ```bash
  npm start
  ```

- **Dev**: Run the app in development mode with hot reloading

  ```bash
  npm run dev
  ```

- **Clean**: Clean the build artifacts

  ```bash
  npm run clean
  ```

- **Type-check**: Perform TypeScript type checking without emitting files
  ```bash
  npm run type-check
  ```

## Configuration

- **TypeScript**: Configuration is in `tsconfig.json`.
