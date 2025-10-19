<img width="1600" height="642" alt="image" src="https://github.com/user-attachments/assets/a7491300-77a4-43c1-8fd5-004271a2eb16" />





AI-Powered Crypto Technical Analysis Engine
Overview

An intelligent cryptocurrency analysis system that processes user queries through Telegram, generates TradingView charts using Chart-img API, and produces AI-driven technical reports via GPT-4o Vision.
It delivers actionable trading insights, risk/reward analysis, and professional charts instantly to users.

Workflow Summary
1. User Query Input

User sends a cryptocurrency name or symbol (e.g., BTC, Bitcoin) via Telegram.

System automatically converts it into the correct TradingView pair format (e.g., BINANCE:BTCUSDT).

2. Chart Generation

Uses Chart-img API to render a TradingView chart with:

Volume

RSI (Relative Strength Index)

DMI (Directional Movement Index)

Outputs the chart as a JPEG image.

3. Technical Analysis Report

GPT-4o Vision interprets the chart image and generates a structured analysis including:

Current trend and pattern

RSI and DMI indicator readings

Key support/resistance levels

Entry, Stop Loss, and Target levels

Risk/Reward ratio and timeframe

Keeps output under 4,000 characters for Telegram compatibility.

4. Telegram Delivery

Sends both the chart image and text analysis back to the user.

Provides a concise, readable layout for fast decision-making.

Features

Multi-indicator chart generation (RSI, Volume, DMI)

GPT-4o Vision–based analysis and summarization

Auto symbol conversion for any coin/pair

Actionable trade setups with R/R metrics

50-message context memory for conversational flow

Telegram integration for instant interaction

Technology Stack

n8n – Workflow orchestration

GPT-4o Vision – Chart interpretation and report generation

Chart-img API – TradingView chart rendering

Telegram Bot API – Front-end chat interface

Summary

This AI-powered workflow automates technical crypto analysis end-to-end — from chart generation to trading insights — enabling fast, data-driven decisions directly from Telegram.
