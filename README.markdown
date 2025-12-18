Insurance Certificate Issuance System README
English
Overview
This is a comprehensive web-based application designed for managing and issuing cargo insurance certificates. The system provides a complete workflow for insurance representatives to register insurance policies, issue certificates, manage remaining policy balances, and generate professional printable documents.
Key Features

Certificate Issuance: Complete wizard-based interface for creating insurance certificates with automatic balance deduction from selected policies
Policy Management: Registration and management of insurance policies with real-time remaining balance tracking
Document Printing: Professional A5-sized certificate printing with company logo support and precise formatting
Data Management: Full CRUD operations for companies, policies, and issued certificates
Balance Control: Automatic deduction from policy balances when certificates are issued, with validation to prevent overdrawing
Certificate Editing: Full editing capabilities including transferring certificates between policies with automatic balance adjustments
Backup and Restore: Complete data backup and restoration functionality using JSON files
Professional Printing: Optimized print layout specifically formatted for A5 paper with proper margins and professional appearance

System Requirements

Modern web browser (Chrome, Firefox, Edge, Safari)
Local storage support (all modern browsers)

Usage Instructions

Login: Enter password "1234" to access the application
Primary Workflow:StepAction1Register insurance companies and policies2Select company and policy with available balance3Enter certificate details including cottage numbers, quantity, and value4System validates available balance and deducts the certificate value5Print professional certificate with all required information
Key Functions:FunctionPurposeCertificate RegistrationPrimary function for issuing new certificatesPolicy ManagementRegister and edit insurance policiesHistoryView and manage all issued certificatesBalance ReportMonitor remaining balances for each policyBackup/RestoreComplete data preservation and recovery

Technical Implementation

Single-page web application with client-side data storage using localStorage
Responsive interface optimized for desktop use
Professional print formatting specifically designed for A5 paper size
Automatic duplicate cottage number detection and warning
Comprehensive balance management with validation and rollback capabilities


فارسی
بررسی اجمالی
این برنامه یک سیستم کامل مبتنی بر وب برای مدیریت و صدور گواهی‌های بیمه باربری است. این سیستم امکان ثبت بیمه‌نامه‌ها، صدور اسناد بیمه، مدیریت مانده بیمه‌نامه‌ها و تولید اسناد قابل چاپ حرفه‌ای را فراهم می‌کند.
ویژگی‌های کلیدی

صدور گواهی: رابط کاربری کامل برای ایجاد اسناد بیمه با کسر خودکار مبلغ از مانده بیمه‌نامه انتخاب شده
مدیریت بیمه‌نامه: ثبت و مدیریت بیمه‌نامه‌ها با ردیابی مانده به صورت لحظه‌ای
چاپ اسناد: چاپ حرفه‌ای اسناد در اندازه A5 با پشتیبانی از لوگوی شرکت و فرمت‌بندی دقیق
مدیریت داده‌ها: عملیات کامل ایجاد، ویرایش، مشاهده و حذف شرکت‌ها، بیمه‌نامه‌ها و اسناد
کنترل مانده: کسر خودکار از مانده بیمه‌نامه هنگام صدور سند با بررسی عدم برداشت بیش از حد
ویرایش اسناد: امکان ویرایش کامل اسناد شامل انتقال بین بیمه‌نامه‌ها با تعدیل خودکار مانده‌ها
پشتیبان‌گیری: امکان پشتیبان‌گیری کامل و بازیابی اطلاعات با استفاده از فایل‌های JSON

الزامات سیستم

مرورگر وب مدرن
پشتیبانی از Local Storage

نحوه استفاده

ورود: رمز عبور "1234" را وارد نمایید
روند کاری:مرحلهاقدام1ثبت شرکت‌ها و بیمه‌نامه‌ها2انتخاب شرکت و بیمه‌نامه دارای مانده3وارد کردن مشخصات سند شامل شماره کوتاژها، تعداد و ارزش4بررسی مانده و کسر خودکار مبلغ سند از بیمه‌نامه5چاپ سند حرفه‌ای با تمام اطلاعات مورد نیاز

قابلیت‌های اصلی

ثبت و صدور اسناد بیمه با کنترل کامل مانده
مشاهده و ویرایش کامل سوابق اسناد صادر شده
گزارش‌گیری از مانده بیمه‌نامه‌ها
پشتیبان‌گیری و بازیابی کامل اطلاعات


中文
系统概述
这是一个基于Web的全面货物保险证书管理与发行系统。该系统为保险代理机构提供了完整的保险证书发行工作流程，包括保险单登记、证书发行、保险单余额管理以及专业可打印文档的生成。
主要功能特性

证书发行: 基于向导的完整界面，用于创建保险证书并自动从所选保险单中扣除余额
保单管理: 保险单的登记和管理，实时跟踪剩余余额
文档打印: 专业A5尺寸证书打印，支持公司徽标和精确的格式化
数据管理: 对公司、保单和已发行证书的完整增删改查操作
余额控制: 在发行证书时自动从保单余额中扣除金额，并验证防止透支
证书编辑: 完整的编辑功能，包括在不同保单之间转移证书并自动调整余额
备份与恢复: 使用JSON文件实现完整的数据备份和恢复功能

系统要求

现代网页浏览器
支持本地存储功能

使用方法

登录: 输入密码"1234"进入系统
主要工作流程:步骤操作1登记保险公司和保险单2选择具有可用余额的保险公司和保险单3输入证书详细信息，包括货单号码、数量和价值4系统验证可用余额并自动扣除证书价值5打印包含所有必要信息的专业证书

主要功能

保险证书的登记和发行，具备完整的余额控制
查看和完整编辑已发行的证书记录
生成保险单剩余余额报告
完整的数据备份和恢复功能