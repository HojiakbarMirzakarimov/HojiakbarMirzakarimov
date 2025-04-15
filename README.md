import React from 'react';
import { FaHtml5, FaCss3Alt, FaJs, FaReact, FaSass, FaBootstrap, FaGithub, FaWhatsapp } from 'react-icons/fa';

const Profile = () => {
  return (
    <div style={{ textAlign: 'center' }}>
      <h1>Привет, я Hojiakbar! 👋</h1>
      <p>Я **фронтенд-разработчик**, специализируюсь на создании быстрых и красивых интерфейсов. Работаю с современными технологиями, такими как **React**, **Tailwind CSS**, **Zustand**, и многими другими.</p>
      <p><strong>Мои навыки:</strong></p>
      <p>HTML5, CSS3, JavaScript (ES6+), JSX, TypeScript, React.js, Tailwind CSS, SCSS, Bootstrap</p>
      <p><strong>Контакты:</strong></p>
      <p>Telegram: @08hoji00, WhatsApp: +996 555 251 506</p>
      
      <div style={{ display: 'flex', justifyContent: 'center', gap: '20px' }}>
        <FaHtml5 size={50} />
        <FaCss3Alt size={50} />
        <FaJs size={50} />
        <FaReact size={50} />
        <FaSass size={50} />
        <FaBootstrap size={50} />
        <FaGithub size={50} />
        <a href="https://wa.me/996555251506" target="_blank" rel="noopener noreferrer">
          <FaWhatsapp size={50} />
        </a>
      </div>
    </div>
  );
};

export default Profile;
