### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 235ms | 235ms | 6014944.08
| ChannelStore.GetMembers | avg | 99ms | 319ms | 220ms | 222.80
| UserStore.GetProfilesNotInChannel | avg | 189ms | 339ms | 150ms | 79.21
| StatusStore.UpdateExpiredDNDStatuses | avg | 9ms | 16ms | 7ms | 74.39
| PostStore.GetPostReminderMetadata | avg | 175ms | 302ms | 127ms | 72.45
| PostPersistentNotificationStore.DeleteExpired | avg | 5ms | 8ms | 3ms | 55.95
| ChannelStore.CreateSidebarCategory | avg | 41ms | 63ms | 22ms | 53.98
| RoleStore.ChannelHigherScopedPermissions | avg | 130ms | 190ms | 60ms | 46.19
| UserStore.GetProfilesInChannel | avg | 86ms | 124ms | 38ms | 44.21
| JobStore.GetNewestJobByStatusesAndType | avg | 122ms | 171ms | 49ms | 40.04
| PostPersistentNotificationStore.Get | avg | 5ms | 7ms | 2ms | 38.55
| StatusStore.GetByIds | avg | 154ms | 197ms | 43ms | 27.96
| ThreadStore.Get | avg | 191ms | 238ms | 47ms | 24.54
| UserAccessTokenStore.GetByToken | avg | 106ms | 131ms | 25ms | 23.63
| ChannelStore.Save | avg | 209ms | 247ms | 38ms | 18.21
| PostStore.Update | avg | 29ms | 34ms | 5ms | 17.19
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 172ms | 200ms | 28ms | 16.30
| TeamStore.GetActiveMemberCount | avg | 464ms | 528ms | 64ms | 13.80
| ChannelStore.GetPinnedPostCount | avg | 176ms | 194ms | 18ms | 10.24
| PostStore.SearchPostsForUser | avg | 240ms | 262ms | 22ms | 9.16
| ChannelStore.SearchGroupChannels | avg | 184ms | 200ms | 16ms | 8.70
| PostPriorityStore.GetForPost | avg | 144ms | 155ms | 11ms | 7.62
| ChannelStore.Autocomplete | avg | 3.527s | 3.793s | 266ms | 7.54
| ChannelStore.GetChannelUnread | avg | 162ms | 174ms | 12ms | 7.42
| PostStore.GetPostsAfter | avg | 151ms | 162ms | 11ms | 7.30
| JobStore.Get | avg | 151ms | 162ms | 11ms | 7.29
| EmojiStore.GetMultipleByName | avg | 202ms | 214ms | 12ms | 5.95
| ChannelStore.AutocompleteInTeamForSearch | avg | 588ms | 616ms | 28ms | 4.76
| PreferenceStore.GetAll | avg | 177ms | 184ms | 7ms | 3.95
| ChannelStore.GetMemberForPost | avg | 201ms | 208ms | 7ms | 3.48
| TeamStore.Get | avg | 160ms | 165ms | 5ms | 3.13
| PostStore.GetSingle | avg | 164ms | 169ms | 5ms | 3.04
| TeamStore.GetTotalMemberCount | avg | 434ms | 447ms | 13ms | 2.99
| ChannelStore.UpdateSidebarCategories | avg | 537ms | 553ms | 16ms | 2.98
| ThreadStore.GetThreadsForUser | avg | 192ms | 197ms | 5ms | 2.60
| LinkMetadataStore.Get | avg | 168ms | 172ms | 4ms | 2.38
| PostStore.GetPostsSince | avg | 217ms | 222ms | 5ms | 2.30
| TeamStore.GetTeamsByUserId | avg | 137ms | 140ms | 3ms | 2.19
| UserStore.Search | avg | 393ms | 401ms | 8ms | 2.03
| PostAcknowledgementStore.GetForPosts | avg | 274ms | 279ms | 5ms | 1.83
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 116ms | 118ms | 2ms | 1.72
| PostPriorityStore.GetForPosts | avg | 281ms | 285ms | 4ms | 1.42
| UserStore.GetUnreadCount | avg | 144ms | 146ms | 2ms | 1.39
| PostStore.AnalyticsPostCount | avg | 2.934s | 2.974s | 40ms | 1.36
| EmojiStore.GetByName | avg | 175ms | 177ms | 2ms | 1.14
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 1.98s | 1.975s | 39898.22
| UserStore.GetProfilesNotInChannel | p99 | 977ms | 4.6s | 3.623s | 370.96
| StatusStore.UpdateExpiredDNDStatuses | p99 | 48ms | 205ms | 157ms | 330.53
| ChannelStore.GetMembers | p99 | 248ms | 980ms | 732ms | 295.46
| PostStore.GetPostReminderMetadata | p99 | 928ms | 2.35s | 1.422s | 153.18
| JobStore.GetNewestJobByStatusesAndType | p99 | 855ms | 2.13s | 1.275s | 149.12
| TeamStore.GetActiveMemberCount | p99 | 986ms | 2.26s | 1.274s | 129.21
| StatusStore.GetByIds | p99 | 988ms | 2.067s | 1.079s | 109.18
| JobStore.Get | p99 | 915ms | 1.863s | 948ms | 103.61
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 1.03s | 2.087s | 1.057s | 102.62
| LinkMetadataStore.Save | p99 | 41ms | 76ms | 35ms | 84.85
| RoleStore.ChannelHigherScopedPermissions | p99 | 917ms | 1.574s | 657ms | 71.66
| JobStore.Save | p99 | 46ms | 79ms | 33ms | 71.03
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.476s | 3.744s | 1.268s | 51.21
| JobStore.UpdateStatusOptimistically | p99 | 57ms | 79ms | 22ms | 38.60
| FileInfoStore.AttachToPost | p99 | 95ms | 127ms | 32ms | 33.61
| FileInfoStore.SetContent | p99 | 138ms | 182ms | 44ms | 31.97
| TeamStore.GetTeamsByUserId | p99 | 989ms | 1.205s | 216ms | 21.84
| UserStore.GetUnreadCount | p99 | 1.357s | 1.604s | 247ms | 18.20
| PostPersistentNotificationStore.DeleteExpired | p99 | 75ms | 88ms | 13ms | 17.33
| PostPersistentNotificationStore.Get | p99 | 75ms | 86ms | 11ms | 14.67
| PostStore.GetPostReminders | p99 | 205ms | 228ms | 23ms | 11.22
| PluginStore.SetWithOptions | p99 | 100ms | 111ms | 11ms | 11.04
| UserStore.GetAllProfilesInChannel | p99 | 2.539s | 2.805s | 266ms | 10.48
| StatusStore.SaveOrUpdate | p99 | 164ms | 181ms | 17ms | 10.34
| ChannelStore.SearchGroupChannels | p99 | 1.847s | 2.026s | 179ms | 9.69
| ThreadStore.GetTotalUnreadMentions | p99 | 1.095s | 1.196s | 101ms | 9.22
| StatusStore.Get | p99 | 716ms | 778ms | 62ms | 8.65
| EmojiStore.GetMultipleByName | p99 | 850ms | 923ms | 73ms | 8.59
| PreferenceStore.GetAll | p99 | 1.518s | 1.645s | 127ms | 8.37
| PostStore.SearchPostsForUser | p99 | 2.323s | 2.49s | 167ms | 7.19
| UserStore.GetMany | p99 | 900ms | 953ms | 53ms | 5.89
| ChannelStore.GetChannelUnread | p99 | 1.61s | 1.703s | 93ms | 5.78
| ChannelStore.SaveMember | p99 | 3.426s | 3.623s | 197ms | 5.75
| ChannelStore.GetChannelsByUser | p99 | 1.347s | 1.421s | 74ms | 5.49
| ChannelStore.GetMemberForPost | p99 | 2.007s | 2.114s | 107ms | 5.33
| ChannelStore.GetPinnedPostCount | p99 | 1.993s | 2.098s | 105ms | 5.27
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 907ms | 954ms | 47ms | 5.18
| PreferenceStore.DeleteCategoryAndName | p99 | 89ms | 93ms | 4ms | 4.52
| UserStore.UpdateUpdateAt | p99 | 68ms | 71ms | 3ms | 4.44
| ChannelStore.GetAllChannelMembersForUser | p99 | 861ms | 899ms | 38ms | 4.41
| ThreadStore.GetTotalUnreadThreads | p99 | 1.036s | 1.08s | 44ms | 4.25
| EmojiStore.GetByName | p99 | 1.882s | 1.95s | 68ms | 3.61
| ChannelStore.CreateInitialSidebarCategories | p99 | 934ms | 966ms | 32ms | 3.43
| ThreadStore.GetThreadsForUser | p99 | 1.901s | 1.962s | 61ms | 3.21
| TeamStore.Get | p99 | 1.755s | 1.809s | 54ms | 3.08
| TeamStore.GetMember | p99 | 168ms | 173ms | 5ms | 2.97
| GroupStore.GetByName | p99 | 775ms | 798ms | 23ms | 2.97
| PostPriorityStore.GetForPost | p99 | 1.717s | 1.765s | 48ms | 2.79
| UserStore.Save | p99 | 361ms | 370ms | 9ms | 2.49
| PostStore.GetEtag | p99 | 1.54s | 1.577s | 37ms | 2.40
| PostStore.GetSingle | p99 | 1.818s | 1.851s | 33ms | 1.82
| UserStore.IsEmpty | p99 | 643ms | 654ms | 11ms | 1.71
| PostStore.GetPostsSince | p99 | 1.936s | 1.965s | 29ms | 1.50
| ThreadStore.GetThreadFollowers | p99 | 1.898s | 1.925s | 27ms | 1.42
| ChannelStore.CreateSidebarCategory | p99 | 243ms | 246ms | 3ms | 1.24
| ChannelStore.GetMembersForUser | p99 | 1.74s | 1.758s | 18ms | 1.03
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 7ms | 2ms | -5ms | -67.25
| SessionStore.Remove | avg | 9ms | 5ms | -4ms | -46.31
| PostStore.SetPostReminder | avg | 23ms | 14ms | -9ms | -39.17
| SessionStore.GetSessionsExpired | avg | 149ms | 104ms | -45ms | -30.17
| PluginStore.List | avg | 220ms | 156ms | -64ms | -29.06
| JobStore.UpdateOptimistically | avg | 8ms | 6ms | -2ms | -26.08
| JobStore.UpdateStatus | avg | 8ms | 6ms | -2ms | -25.34
| BotStore.Get | avg | 225ms | 170ms | -55ms | -24.44
| UserStore.Update | avg | 15ms | 12ms | -3ms | -19.88
| ChannelStore.GetSidebarCategory | avg | 284ms | 228ms | -56ms | -19.72
| JobStore.GetCountByStatusAndType | avg | 194ms | 157ms | -37ms | -19.04
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 205ms | 172ms | -33ms | -16.06
| PreferenceStore.DeleteCategoryAndName | avg | 13ms | 11ms | -2ms | -14.82
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 44ms | 38ms | -6ms | -13.70
| ReactionStore.GetForPost | avg | 186ms | 162ms | -24ms | -12.90
| UserStore.Count | avg | 368ms | 324ms | -44ms | -11.96
| PostStore.Delete | avg | 242ms | 214ms | -28ms | -11.55
| UserStore.GetByUsername | avg | 186ms | 170ms | -16ms | -8.61
| SessionStore.GetLRUSessions | avg | 132ms | 121ms | -11ms | -8.36
| ChannelStore.CreateDirectChannel | avg | 593ms | 545ms | -48ms | -8.10
| UserStore.Get | avg | 77ms | 72ms | -5ms | -6.48
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 139ms | 131ms | -8ms | -5.75
| PostPersistentNotificationStore.GetSingle | avg | 192ms | 181ms | -11ms | -5.72
| SessionStore.Save | avg | 131ms | 124ms | -7ms | -5.36
| UserStore.GetProfileByIds | avg | 104ms | 99ms | -5ms | -4.81
| DraftStore.GetDraftsForUser | avg | 209ms | 199ms | -10ms | -4.78
| TeamStore.GetTeamsForUser | avg | 105ms | 100ms | -5ms | -4.77
| FileInfoStore.GetByIds | avg | 209ms | 200ms | -9ms | -4.31
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 319ms | 306ms | -13ms | -4.08
| ChannelStore.GetMemberLastViewedAt | avg | 112ms | 108ms | -4ms | -3.58
| UserStore.GetForLogin | avg | 116ms | 112ms | -4ms | -3.44
| FileInfoStore.Get | avg | 118ms | 114ms | -4ms | -3.39
| ThreadStore.GetMembershipForUser | avg | 178ms | 172ms | -6ms | -3.38
| FileInfoStore.GetForPost | avg | 210ms | 203ms | -7ms | -3.33
| PostStore.GetPostsByThread | avg | 185ms | 179ms | -6ms | -3.24
| ThreadStore.GetThreadUnreadReplyCount | avg | 200ms | 194ms | -6ms | -3.00
| ChannelStore.GetMemberCount | avg | 510ms | 495ms | -15ms | -2.94
| ChannelStore.GetPublicChannelsForTeam | avg | 217ms | 211ms | -6ms | -2.76
| PostStore.GetPosts | avg | 111ms | 108ms | -3ms | -2.71
| ChannelStore.GetGuestCount | avg | 160ms | 156ms | -4ms | -2.51
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 132ms | 129ms | -3ms | -2.27
| SessionStore.Get | avg | 132ms | 129ms | -3ms | -2.27
| TeamStore.GetChannelUnreadsForAllTeams | avg | 134ms | 131ms | -3ms | -2.24
| JobStore.GetAllByStatus | avg | 168ms | 165ms | -3ms | -1.78
| ChannelStore.GetByName | avg | 116ms | 114ms | -2ms | -1.73
| ChannelStore.GetFileCount | avg | 120ms | 118ms | -2ms | -1.67
| ThreadStore.GetTotalUnreadThreads | avg | 131ms | 129ms | -2ms | -1.52
| PostAcknowledgementStore.GetForPost | avg | 151ms | 149ms | -2ms | -1.33
| UserTermsOfServiceStore.GetByUser | avg | 152ms | 150ms | -2ms | -1.31
| ChannelStore.GetChannelsByUser | avg | 160ms | 158ms | -2ms | -1.25
| ChannelStore.GetTeamChannels | avg | 170ms | 168ms | -2ms | -1.17
| GroupStore.GetGroups | avg | 174ms | 172ms | -2ms | -1.15
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SetPostReminder | p99 | 445ms | 95ms | -350ms | -78.65
| SessionStore.Remove | p99 | 87ms | 23ms | -64ms | -73.56
| JobStore.UpdateStatus | p99 | 122ms | 43ms | -79ms | -64.51
| PluginStore.List | p99 | 2.19s | 897ms | -1.293s | -59.04
| BotStore.Get | p99 | 2.05s | 850ms | -1.2s | -58.54
| UserStore.GetByUsername | p99 | 2.148s | 976ms | -1.172s | -54.57
| JobStore.UpdateOptimistically | p99 | 122ms | 58ms | -64ms | -52.26
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| TokenStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| DesktopTokensStore.DeleteOlderThan | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.UpdateSidebarCategories | p99 | 4.437s | 2.391s | -2.046s | -46.11
| ChannelStore.CreateDirectChannel | p99 | 4.4s | 2.494s | -1.906s | -43.32
| PostAcknowledgementStore.GetForPost | p99 | 1.717s | 987ms | -730ms | -42.50
| ChannelStore.GetSidebarCategory | p99 | 2.75s | 1.735s | -1.015s | -36.91
| UserStore.Update | p99 | 149ms | 97ms | -52ms | -34.96
| JobStore.GetCountByStatusAndType | p99 | 2.825s | 1.847s | -978ms | -34.62
| ReactionStore.GetForPost | p99 | 2.009s | 1.364s | -645ms | -32.10
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 2.185s | 1.54s | -645ms | -29.52
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 1.537s | 1.134s | -403ms | -26.22
| SessionStore.GetLRUSessions | p99 | 1.191s | 947ms | -244ms | -20.48
| JobStore.GetAllByStatus | p99 | 1.718s | 1.387s | -331ms | -19.26
| UserStore.GetProfileByIds | p99 | 1.212s | 992ms | -220ms | -18.15
| FileInfoStore.GetByIds | p99 | 2.136s | 1.837s | -299ms | -14.00
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 84ms | 73ms | -11ms | -13.08
| PostStore.GetPostsAfter | p99 | 1.877s | 1.676s | -201ms | -10.71
| SessionStore.Save | p99 | 1.068s | 958ms | -110ms | -10.30
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 74ms | 67ms | -7ms | -9.41
| UserStore.AutocompleteUsersInChannel | p99 | 2.98s | 2.701s | -279ms | -9.36
| SessionStore.Get | p99 | 1.077s | 984ms | -93ms | -8.64
| PostPersistentNotificationStore.GetSingle | p99 | 1.926s | 1.765s | -161ms | -8.36
| UserTermsOfServiceStore.GetByUser | p99 | 1.301s | 1.21s | -91ms | -7.00
| PostStore.GetPostsByThread | p99 | 1.984s | 1.865s | -119ms | -6.00
| ChannelStore.IncrementMentionCount | p99 | 77ms | 73ms | -4ms | -5.22
| ThreadStore.GetThreadUnreadReplyCount | p99 | 2.031s | 1.928s | -103ms | -5.07
| SessionStore.UpdateLastActivityAt | p99 | 82ms | 78ms | -4ms | -4.89
| WebhookStore.GetOutgoingByTeam | p99 | 1.915s | 1.825s | -90ms | -4.70
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 1.137s | 1.084s | -53ms | -4.66
| DraftStore.GetDraftsForUser | p99 | 2.124s | 2.032s | -92ms | -4.33
| SystemStore.GetByName | p99 | 71ms | 68ms | -3ms | -4.24
| PostStore.Delete | p99 | 2.155s | 2.065s | -90ms | -4.18
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 216ms | 207ms | -9ms | -4.18
| ThreadStore.GetMembershipForUser | p99 | 1.914s | 1.838s | -76ms | -3.97
| UserStore.GetProfilesByUsernames | p99 | 1.032s | 997ms | -35ms | -3.39
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.996s | 1.93s | -66ms | -3.31
| FileInfoStore.Save | p99 | 92ms | 89ms | -3ms | -3.28
| ChannelStore.UpdateLastViewedAt | p99 | 185ms | 179ms | -6ms | -3.24
| TeamStore.GetTeamsForUser | p99 | 925ms | 896ms | -29ms | -3.13
| ThreadStore.UpdateMembership | p99 | 96ms | 93ms | -3ms | -3.11
| PostStore.GetPostIdAfterTime | p99 | 77ms | 75ms | -2ms | -2.58
| GroupStore.GetGroups | p99 | 1.884s | 1.837s | -47ms | -2.49
| ChannelStore.GetMemberLastViewedAt | p99 | 949ms | 926ms | -23ms | -2.42
| UserStore.GetForLogin | p99 | 951ms | 928ms | -23ms | -2.42
| ThreadStore.MaintainMembership | p99 | 210ms | 205ms | -5ms | -2.38
| PostStore.GetPosts | p99 | 931ms | 909ms | -22ms | -2.36
| UserAccessTokenStore.GetByToken | p99 | 923ms | 902ms | -21ms | -2.28
| ChannelStore.GetTeamChannels | p99 | 491ms | 480ms | -11ms | -2.24
| PostStore.GetPostIdBeforeTime | p99 | 90ms | 88ms | -2ms | -2.23
| ThreadStore.GetTeamsUnreadForUser | p99 | 2.15s | 2.103s | -47ms | -2.19
| DraftStore.Upsert | p99 | 93ms | 91ms | -2ms | -2.16
| StatusStore.UpdateLastActivityAt | p99 | 94ms | 92ms | -2ms | -2.12
| DraftStore.Delete | p99 | 96ms | 94ms | -2ms | -2.09
| ThreadStore.MarkAllAsReadByChannels | p99 | 97ms | 95ms | -2ms | -2.06
| PreferenceStore.Get | p99 | 1.739s | 1.704s | -35ms | -2.01
| ThreadStore.Get | p99 | 2s | 1.96s | -40ms | -2.00
| FileInfoStore.GetForPost | p99 | 2.157s | 2.116s | -41ms | -1.90
| ChannelStore.Save | p99 | 2.215s | 2.174s | -41ms | -1.85
| DraftStore.Get | p99 | 2.062s | 2.025s | -37ms | -1.79
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 2.422s | 2.38s | -42ms | -1.73
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 1.105s | 1.086s | -19ms | -1.72
| ProductNoticesStore.View | p99 | 471ms | 463ms | -8ms | -1.70
| PostStore.Save | p99 | 240ms | 236ms | -4ms | -1.66
| ChannelStore.GetGuestCount | p99 | 1.392s | 1.371s | -21ms | -1.51
| ChannelStore.GetMember | p99 | 207ms | 204ms | -3ms | -1.45
| PostStore.Update | p99 | 233ms | 230ms | -3ms | -1.29
| TeamStore.GetAllPage | p99 | 988ms | 977ms | -11ms | -1.11
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 100ms | 320ms | 220ms | 220.94
| createCategoryForTeamForUser | avg | 243ms | 430ms | 187ms | 76.87
| createGroupChannel | avg | 2.494s | 2.996s | 502ms | 20.13
| getTeamStats | avg | 544ms | 623ms | 79ms | 14.53
| deletePost | avg | 630ms | 699ms | 69ms | 10.96
| getPostsForChannel | avg | 1.791s | 1.966s | 175ms | 9.77
| searchGroupChannels | avg | 184ms | 200ms | 16ms | 8.70
| searchAllChannels | avg | 3.532s | 3.803s | 271ms | 7.67
| getChannelUnread | avg | 175ms | 188ms | 13ms | 7.41
| unfollowThreadByUser | avg | 449ms | 480ms | 31ms | 6.91
| patchPost | avg | 1.166s | 1.235s | 69ms | 5.92
| setPostReminder | avg | 972ms | 1.019s | 47ms | 4.84
| autocompleteChannelsForTeamForSearch | avg | 588ms | 616ms | 28ms | 4.76
| getPreferences | avg | 180ms | 188ms | 8ms | 4.43
| getTeamsForUser | avg | 138ms | 141ms | 3ms | 2.18
| searchUsers | avg | 397ms | 405ms | 8ms | 2.01
| updateCategoriesForTeamForUser | avg | 1.25s | 1.269s | 19ms | 1.52
| uploadFileStream | avg | 437ms | 443ms | 6ms | 1.37
| saveReaction | avg | 552ms | 559ms | 7ms | 1.27
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 496ms | 2.425s | 1.929s | 389.04
| getChannelMembers | p99 | 248ms | 980ms | 732ms | 295.46
| getTeamStats | p99 | 991ms | 2.26s | 1.269s | 128.02
| followThreadByUser | p99 | 980ms | 2.23s | 1.25s | 127.50
| autocompleteChannelsForTeamForSearch | p99 | 2.476s | 3.744s | 1.268s | 51.21
| getTeamMember | p99 | 247ms | 326ms | 79ms | 31.98
| getTeamsForUser | p99 | 990ms | 1.211s | 221ms | 22.31
| patchPost | p99 | 8.42s | 10s | 1.58s | 18.77
| searchGroupChannels | p99 | 1.847s | 2.026s | 179ms | 9.69
| getPreferences | p99 | 1.564s | 1.7s | 136ms | 8.70
| saveReaction | p99 | 3.82s | 4.152s | 332ms | 8.69
| getChannelUnread | p99 | 1.721s | 1.87s | 149ms | 8.66
| setPostReminder | p99 | 4.45s | 4.75s | 300ms | 6.74
| getChannelsForUser | p99 | 1.347s | 1.421s | 74ms | 5.49
| removeUserCustomStatus | p99 | 974ms | 991ms | 17ms | 1.74
| upsertDraft | p99 | 978ms | 989ms | 11ms | 1.12
| getChannelMembersForTeamForUser | p99 | 1.747s | 1.766s | 19ms | 1.09
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 341ms | 264ms | -77ms | -22.59
| removeUserCustomStatus | avg | 326ms | 280ms | -46ms | -14.12
| createDirectChannel | avg | 1.343s | 1.243s | -100ms | -7.45
| addChannelMember | avg | 2.651s | 2.457s | -194ms | -7.32
| getProfileImage | avg | 92ms | 86ms | -6ms | -6.55
| updatePreferences | avg | 33ms | 31ms | -2ms | -5.99
| searchPostsInTeam | avg | 623ms | 587ms | -36ms | -5.78
| getClientConfig | avg | 37ms | 35ms | -2ms | -5.34
| getTeamMembersForUser | avg | 115ms | 109ms | -6ms | -5.23
| login | avg | 545ms | 518ms | -27ms | -4.95
| getUsers | avg | 64ms | 61ms | -3ms | -4.71
| getCategoriesForTeamForUser | avg | 319ms | 307ms | -12ms | -3.76
| getDrafts | avg | 215ms | 208ms | -7ms | -3.25
| getFileThumbnail | avg | 187ms | 181ms | -6ms | -3.21
| createChannel | avg | 2.265s | 2.201s | -64ms | -2.83
| getPublicChannelsForTeam | avg | 219ms | 213ms | -6ms | -2.74
| getChannelMember | avg | 181ms | 177ms | -4ms | -2.22
| getFilePreview | avg | 188ms | 184ms | -4ms | -2.12
| getChannel | avg | 531ms | 521ms | -10ms | -1.88
| getPostsForChannelAroundLastUnread | avg | 599ms | 589ms | -10ms | -1.67
| getAllTeams | avg | 141ms | 139ms | -2ms | -1.42
| getTeamsUnreadForUser | avg | 225ms | 222ms | -3ms | -1.33
| createPost | avg | 3.674s | 3.632s | -42ms | -1.14
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | p99 | 33ms | 5ms | -28ms | -83.90
| createChannel | p99 | 9.25s | 4.933s | -4.317s | -46.67
| createDirectChannel | p99 | 8.542s | 4.664s | -3.878s | -45.40
| unfollowThreadByUser | p99 | 4.417s | 2.466s | -1.951s | -44.17
| updateCategoriesForTeamForUser | p99 | 7.75s | 4.745s | -3.005s | -38.78
| getChannel | p99 | 4.713s | 3.131s | -1.582s | -33.57
| searchPostsInTeam | p99 | 7.995s | 6s | -1.995s | -24.95
| updatePreferences | p99 | 323ms | 256ms | -67ms | -20.76
| getAllTeams | p99 | 1.166s | 1.001s | -165ms | -14.16
| login | p99 | 4.094s | 3.609s | -485ms | -11.85
| getUserStatusesByIds | p99 | 18ms | 16ms | -2ms | -11.28
| autocompleteUsers | p99 | 2.768s | 2.5s | -268ms | -9.68
| getUsersByNames | p99 | 1.09s | 1.027s | -63ms | -5.78
| logout | p99 | 2.11s | 2.005s | -105ms | -4.98
| getUsers | p99 | 871ms | 828ms | -43ms | -4.94
| getUser | p99 | 1.689s | 1.612s | -77ms | -4.56
| getTeamMembersForUser | p99 | 970ms | 937ms | -33ms | -3.40
| deletePost | p99 | 4.425s | 4.275s | -150ms | -3.39
| getDrafts | p99 | 2.154s | 2.082s | -72ms | -3.34
| getPublicChannelsForTeam | p99 | 1.996s | 1.93s | -66ms | -3.31
| getFileThumbnail | p99 | 1.688s | 1.636s | -52ms | -3.08
| deleteDraft | p99 | 2.064s | 2.025s | -39ms | -1.89
| getFilePreview | p99 | 1.562s | 1.533s | -29ms | -1.86
| getCategoriesForTeamForUser | p99 | 2.422s | 2.382s | -40ms | -1.65
| uploadFileStream | p99 | 1.958s | 1.929s | -29ms | -1.48
| updateReadStateThreadByUser | p99 | 8.437s | 8.32s | -117ms | -1.39
| getChannelsForTeamForUser | p99 | 1.812s | 1.788s | -24ms | -1.32
| getTeamsUnreadForUser | p99 | 2.294s | 2.264s | -30ms | -1.31
| getUsersByIds | p99 | 367ms | 363ms | -4ms | -1.09
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 87ms | 1ms | 1.157
| BotStore.Get |  Avg| 225ms| 170ms | -55ms | -24.436
| |  P99| 2.05s| 850ms | -1.2s | -58.537
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 6ms | -1ms | -15.096
| |  P99| 74ms| 67ms | -7ms | -9.407
| ChannelStore.Autocomplete |  Avg| 3.527s| 3.793s | 266ms | 7.542
| |  P99| 9.852s| 9.884s | 32ms | 0.325
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 588ms| 616ms | 28ms | 4.763
| |  P99| 2.476s| 3.744s | 1.268s | 51.214
| ChannelStore.CreateDirectChannel |  Avg| 593ms| 545ms | -48ms | -8.096
| |  P99| 4.4s| 2.494s | -1.906s | -43.319
| ChannelStore.CreateInitialSidebarCategories |  Avg| 138ms| 138ms | 0s | 0.000
| |  P99| 934ms| 966ms | 32ms | 3.426
| ChannelStore.CreateSidebarCategory |  Avg| 41ms| 63ms | 22ms | 53.976
| |  P99| 243ms| 246ms | 3ms | 1.237
| ChannelStore.Get |  Avg| 207ms| 209ms | 2ms | 0.966
| |  P99| 1.932s| 1.943s | 11ms | 0.570
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 172ms| 200ms | 28ms | 16.301
| |  P99| 1.03s| 2.087s | 1.057s | 102.619
| ChannelStore.GetAllChannelMembersForUser |  Avg| 92ms| 93ms | 1ms | 1.089
| |  P99| 861ms| 899ms | 38ms | 4.413
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 205ms| 172ms | -33ms | -16.064
| |  P99| 2.185s| 1.54s | -645ms | -29.520
| ChannelStore.GetByName |  Avg| 116ms| 114ms | -2ms | -1.731
| |  P99| 967ms| 971ms | 4ms | 0.414
| ChannelStore.GetChannelUnread |  Avg| 162ms| 174ms | 12ms | 7.424
| |  P99| 1.61s| 1.703s | 93ms | 5.776
| ChannelStore.GetChannels |  Avg| 177ms| 177ms | 0s | 0.000
| |  P99| 1.787s| 1.772s | -15ms | -0.839
| ChannelStore.GetChannelsByUser |  Avg| 160ms| 158ms | -2ms | -1.253
| |  P99| 1.347s| 1.421s | 74ms | 5.493
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 155ms| 155ms | 0s | 0.000
| |  P99| 1.607s| 1.609s | 2ms | 0.124
| ChannelStore.GetFileCount |  Avg| 120ms| 118ms | -2ms | -1.671
| |  P99| 923ms| 932ms | 9ms | 0.975
| ChannelStore.GetGuestCount |  Avg| 160ms| 156ms | -4ms | -2.508
| |  P99| 1.392s| 1.371s | -21ms | -1.509
| ChannelStore.GetMember |  Avg| 13ms| 12ms | -1ms | -7.812
| |  P99| 207ms| 204ms | -3ms | -1.451
| ChannelStore.GetMemberCount |  Avg| 510ms| 495ms | -15ms | -2.943
| |  P99| 2.262s| 2.243s | -19ms | -0.840
| ChannelStore.GetMemberForPost |  Avg| 201ms| 208ms | 7ms | 3.476
| |  P99| 2.007s| 2.114s | 107ms | 5.331
| ChannelStore.GetMemberLastViewedAt |  Avg| 112ms| 108ms | -4ms | -3.585
| |  P99| 949ms| 926ms | -23ms | -2.424
| ChannelStore.GetMembers |  Avg| 99ms| 319ms | 220ms | 222.800
| |  P99| 248ms| 980ms | 732ms | 295.459
| ChannelStore.GetMembersForUser |  Avg| 169ms| 169ms | 0s | 0.000
| |  P99| 1.74s| 1.758s | 18ms | 1.035
| ChannelStore.GetPinnedPostCount |  Avg| 176ms| 194ms | 18ms | 10.244
| |  P99| 1.993s| 2.098s | 105ms | 5.268
| ChannelStore.GetPublicChannelsForTeam |  Avg| 217ms| 211ms | -6ms | -2.762
| |  P99| 1.996s| 1.93s | -66ms | -3.306
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 319ms| 306ms | -13ms | -4.080
| |  P99| 2.422s| 2.38s | -42ms | -1.734
| ChannelStore.GetSidebarCategory |  Avg| 284ms| 228ms | -56ms | -19.716
| |  P99| 2.75s| 1.735s | -1.015s | -36.912
| ChannelStore.GetTeamChannels |  Avg| 170ms| 168ms | -2ms | -1.175
| |  P99| 491ms| 480ms | -11ms | -2.241
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 73ms | -4ms | -5.219
| ChannelStore.Save |  Avg| 209ms| 247ms | 38ms | 18.212
| |  P99| 2.215s| 2.174s | -41ms | -1.851
| ChannelStore.SaveMember |  Avg| 495ms| 498ms | 3ms | 0.606
| |  P99| 3.426s| 3.623s | 197ms | 5.751
| ChannelStore.SearchGroupChannels |  Avg| 184ms| 200ms | 16ms | 8.703
| |  P99| 1.847s| 2.026s | 179ms | 9.694
| ChannelStore.UpdateLastViewedAt |  Avg| 16ms| 15ms | -1ms | -6.430
| |  P99| 185ms| 179ms | -6ms | -3.237
| ChannelStore.UpdateSidebarCategories |  Avg| 537ms| 553ms | 16ms | 2.980
| |  P99| 4.437s| 2.391s | -2.046s | -46.108
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 84ms| 73ms | -11ms | -13.084
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 8ms| 9ms | 1ms | 12.161
| |  P99| 89ms| 90ms | 1ms | 1.126
| CommandWebhookStore.Cleanup |  Avg| 3ms| 2ms | -1ms | -30.929
| |  P99| 10ms| 5ms | -5ms | -51.020
| DesktopTokensStore.DeleteOlderThan |  Avg| 7ms| 2ms | -5ms | -67.255
| |  P99| 10ms| 5ms | -5ms | -50.251
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.086
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 44ms| 38ms | -6ms | -13.702
| |  P99| 216ms| 207ms | -9ms | -4.176
| DraftStore.Get |  Avg| 209ms| 207ms | -2ms | -0.957
| |  P99| 2.062s| 2.025s | -37ms | -1.794
| DraftStore.GetDraftsForUser |  Avg| 209ms| 199ms | -10ms | -4.783
| |  P99| 2.124s| 2.032s | -92ms | -4.332
| DraftStore.Upsert |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 91ms | -2ms | -2.156
| EmojiStore.GetByName |  Avg| 175ms| 177ms | 2ms | 1.140
| |  P99| 1.882s| 1.95s | 68ms | 3.613
| EmojiStore.GetMultipleByName |  Avg| 202ms| 214ms | 12ms | 5.955
| |  P99| 850ms| 923ms | 73ms | 8.588
| FileInfoStore.AttachToPost |  Avg| 11ms| 12ms | 1ms | 8.959
| |  P99| 95ms| 127ms | 32ms | 33.615
| FileInfoStore.Get |  Avg| 118ms| 114ms | -4ms | -3.394
| |  P99| 979ms| 975ms | -4ms | -0.409
| FileInfoStore.GetByIds |  Avg| 209ms| 200ms | -9ms | -4.310
| |  P99| 2.136s| 1.837s | -299ms | -13.999
| FileInfoStore.GetForPost |  Avg| 210ms| 203ms | -7ms | -3.332
| |  P99| 2.157s| 2.116s | -41ms | -1.901
| FileInfoStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 89ms | -3ms | -3.278
| FileInfoStore.SetContent |  Avg| 15ms| 16ms | 1ms | 6.698
| |  P99| 138ms| 182ms | 44ms | 31.973
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 116ms| 118ms | 2ms | 1.722
| |  P99| 907ms| 954ms | 47ms | 5.185
| GroupStore.GetByName |  Avg| 89ms| 89ms | 0s | 0.000
| |  P99| 775ms| 798ms | 23ms | 2.967
| GroupStore.GetGroups |  Avg| 174ms| 172ms | -2ms | -1.151
| |  P99| 1.884s| 1.837s | -47ms | -2.495
| JobStore.Get |  Avg| 151ms| 162ms | 11ms | 7.293
| |  P99| 915ms| 1.863s | 948ms | 103.609
| JobStore.GetAllByStatus |  Avg| 168ms| 165ms | -3ms | -1.782
| |  P99| 1.718s| 1.387s | -331ms | -19.261
| JobStore.GetCountByStatusAndType |  Avg| 194ms| 157ms | -37ms | -19.036
| |  P99| 2.825s| 1.847s | -978ms | -34.619
| JobStore.GetNewestJobByStatusesAndType |  Avg| 122ms| 171ms | 49ms | 40.038
| |  P99| 855ms| 2.13s | 1.275s | 149.123
| JobStore.Save |  Avg| 8ms| 9ms | 1ms | 13.091
| |  P99| 46ms| 79ms | 33ms | 71.031
| JobStore.UpdateOptimistically |  Avg| 8ms| 6ms | -2ms | -26.078
| |  P99| 122ms| 58ms | -64ms | -52.257
| JobStore.UpdateStatus |  Avg| 8ms| 6ms | -2ms | -25.343
| |  P99| 122ms| 43ms | -79ms | -64.505
| JobStore.UpdateStatusOptimistically |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 57ms| 79ms | 22ms | 38.603
| LinkMetadataStore.Get |  Avg| 168ms| 172ms | 4ms | 2.377
| |  P99| 1.853s| 1.859s | 6ms | 0.324
| LinkMetadataStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 76ms | 35ms | 84.850
| PluginStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PluginStore.List |  Avg| 220ms| 156ms | -64ms | -29.061
| |  P99| 2.19s| 897ms | -1.293s | -59.042
| PluginStore.SetWithOptions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 100ms| 111ms | 11ms | 11.037
| PostAcknowledgementStore.GetForPost |  Avg| 151ms| 149ms | -2ms | -1.328
| |  P99| 1.717s| 987ms | -730ms | -42.504
| PostAcknowledgementStore.GetForPosts |  Avg| 274ms| 279ms | 5ms | 1.827
| |  P99| 2.481s| 2.475s | -6ms | -0.242
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 8ms | 3ms | 55.948
| |  P99| 75ms| 88ms | 13ms | 17.334
| PostPersistentNotificationStore.Get |  Avg| 5ms| 7ms | 2ms | 38.549
| |  P99| 75ms| 86ms | 11ms | 14.667
| PostPersistentNotificationStore.GetSingle |  Avg| 192ms| 181ms | -11ms | -5.719
| |  P99| 1.926s| 1.765s | -161ms | -8.361
| PostPriorityStore.GetForPost |  Avg| 144ms| 155ms | 11ms | 7.616
| |  P99| 1.717s| 1.765s | 48ms | 2.795
| PostPriorityStore.GetForPosts |  Avg| 281ms| 285ms | 4ms | 1.425
| |  P99| 2.493s| 2.481s | -12ms | -0.481
| PostStore.AnalyticsPostCount |  Avg| 2.934s| 2.974s | 40ms | 1.363
| |  P99| 4.975s| 4.975s | 0s | 0.000
| PostStore.Delete |  Avg| 242ms| 214ms | -28ms | -11.548
| |  P99| 2.155s| 2.065s | -90ms | -4.176
| PostStore.Get |  Avg| 303ms| 302ms | -1ms | -0.330
| |  P99| 2.412s| 2.393s | -19ms | -0.788
| PostStore.GetEtag |  Avg| 165ms| 165ms | 0s | 0.000
| |  P99| 1.54s| 1.577s | 37ms | 2.402
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 75ms | -2ms | -2.584
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 88ms | -2ms | -2.229
| PostStore.GetPostReminderMetadata |  Avg| 175ms| 302ms | 127ms | 72.446
| |  P99| 928ms| 2.35s | 1.422s | 153.180
| PostStore.GetPostReminders |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 205ms| 228ms | 23ms | 11.220
| PostStore.GetPosts |  Avg| 111ms| 108ms | -3ms | -2.708
| |  P99| 931ms| 909ms | -22ms | -2.363
| PostStore.GetPostsAfter |  Avg| 151ms| 162ms | 11ms | 7.300
| |  P99| 1.877s| 1.676s | -201ms | -10.709
| PostStore.GetPostsBefore |  Avg| 166ms| 167ms | 1ms | 0.601
| |  P99| 1.635s| 1.636s | 1ms | 0.061
| PostStore.GetPostsByThread |  Avg| 185ms| 179ms | -6ms | -3.236
| |  P99| 1.984s| 1.865s | -119ms | -5.997
| PostStore.GetPostsSince |  Avg| 217ms| 222ms | 5ms | 2.304
| |  P99| 1.936s| 1.965s | 29ms | 1.498
| PostStore.GetSingle |  Avg| 164ms| 169ms | 5ms | 3.041
| |  P99| 1.818s| 1.851s | 33ms | 1.816
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 26ms| 25ms | -1ms | -3.813
| |  P99| 240ms| 236ms | -4ms | -1.664
| PostStore.SearchPostsForUser |  Avg| 240ms| 262ms | 22ms | 9.159
| |  P99| 2.323s| 2.49s | 167ms | 7.190
| PostStore.SetPostReminder |  Avg| 23ms| 14ms | -9ms | -39.172
| |  P99| 445ms| 95ms | -350ms | -78.653
| PostStore.Update |  Avg| 29ms| 34ms | 5ms | 17.195
| |  P99| 233ms| 230ms | -3ms | -1.290
| PreferenceStore.DeleteCategoryAndName |  Avg| 13ms| 11ms | -2ms | -14.823
| |  P99| 89ms| 93ms | 4ms | 4.520
| PreferenceStore.Get |  Avg| 166ms| 165ms | -1ms | -0.601
| |  P99| 1.739s| 1.704s | -35ms | -2.012
| PreferenceStore.GetAll |  Avg| 177ms| 184ms | 7ms | 3.950
| |  P99| 1.518s| 1.645s | 127ms | 8.368
| PreferenceStore.Save |  Avg| 22ms| 21ms | -1ms | -4.605
| |  P99| 227ms| 225ms | -2ms | -0.882
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 2ms | -1ms | -36.896
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 58ms| 57ms | -1ms | -1.715
| |  P99| 471ms| 463ms | -8ms | -1.699
| ReactionStore.GetForPost |  Avg| 186ms| 162ms | -24ms | -12.899
| |  P99| 2.009s| 1.364s | -645ms | -32.098
| RoleStore.ChannelHigherScopedPermissions |  Avg| 130ms| 190ms | 60ms | 46.193
| |  P99| 917ms| 1.574s | 657ms | 71.663
| RoleStore.GetByNames |  Avg| 0s| 235ms | 235ms | 6014944.080
| |  P99| 5ms| 1.98s | 1.975s | 39898.224
| SessionStore.Get |  Avg| 132ms| 129ms | -3ms | -2.265
| |  P99| 1.077s| 984ms | -93ms | -8.639
| SessionStore.GetLRUSessions |  Avg| 132ms| 121ms | -11ms | -8.358
| |  P99| 1.191s| 947ms | -244ms | -20.481
| SessionStore.GetSessionsExpired |  Avg| 149ms| 104ms | -45ms | -30.170
| |  P99| 484ms| 484ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 139ms| 131ms | -8ms | -5.748
| |  P99| 1.537s| 1.134s | -403ms | -26.218
| SessionStore.Remove |  Avg| 9ms| 5ms | -4ms | -46.313
| |  P99| 87ms| 23ms | -64ms | -73.562
| SessionStore.Save |  Avg| 131ms| 124ms | -7ms | -5.357
| |  P99| 1.068s| 958ms | -110ms | -10.301
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 78ms | -4ms | -4.893
| StatusStore.Get |  Avg| 80ms| 79ms | -1ms | -1.256
| |  P99| 716ms| 778ms | 62ms | 8.654
| StatusStore.GetByIds |  Avg| 154ms| 197ms | 43ms | 27.957
| |  P99| 988ms| 2.067s | 1.079s | 109.183
| StatusStore.SaveOrUpdate |  Avg| 12ms| 13ms | 1ms | 8.132
| |  P99| 164ms| 181ms | 17ms | 10.336
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 16ms | 7ms | 74.394
| |  P99| 48ms| 205ms | 157ms | 330.526
| StatusStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 92ms | -2ms | -2.119
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 71ms| 68ms | -3ms | -4.240
| TeamStore.Get |  Avg| 160ms| 165ms | 5ms | 3.135
| |  P99| 1.755s| 1.809s | 54ms | 3.076
| TeamStore.GetActiveMemberCount |  Avg| 464ms| 528ms | 64ms | 13.799
| |  P99| 986ms| 2.26s | 1.274s | 129.208
| TeamStore.GetAllPage |  Avg| 131ms| 130ms | -1ms | -0.761
| |  P99| 988ms| 977ms | -11ms | -1.113
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 134ms| 131ms | -3ms | -2.243
| |  P99| 1.137s| 1.084s | -53ms | -4.660
| TeamStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 168ms| 173ms | 5ms | 2.973
| TeamStore.GetTeamsByUserId |  Avg| 137ms| 140ms | 3ms | 2.188
| |  P99| 989ms| 1.205s | 216ms | 21.845
| TeamStore.GetTeamsForUser |  Avg| 105ms| 100ms | -5ms | -4.772
| |  P99| 925ms| 896ms | -29ms | -3.134
| TeamStore.GetTotalMemberCount |  Avg| 434ms| 447ms | 13ms | 2.993
| |  P99| 986ms| 987ms | 1ms | 0.101
| TeamStore.SaveMember |  Avg| 227ms| 228ms | 1ms | 0.440
| |  P99| 993ms| 994ms | 1ms | 0.101
| ThreadStore.Get |  Avg| 191ms| 238ms | 47ms | 24.544
| |  P99| 2s| 1.96s | -40ms | -2.000
| ThreadStore.GetMembershipForUser |  Avg| 178ms| 172ms | -6ms | -3.379
| |  P99| 1.914s| 1.838s | -76ms | -3.971
| ThreadStore.GetTeamsUnreadForUser |  Avg| 184ms| 183ms | -1ms | -0.543
| |  P99| 2.15s| 2.103s | -47ms | -2.186
| ThreadStore.GetThreadFollowers |  Avg| 182ms| 183ms | 1ms | 0.550
| |  P99| 1.898s| 1.925s | 27ms | 1.422
| ThreadStore.GetThreadForUser |  Avg| 264ms| 262ms | -2ms | -0.758
| |  P99| 2.327s| 2.305s | -22ms | -0.945
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 200ms| 194ms | -6ms | -3.001
| |  P99| 2.031s| 1.928s | -103ms | -5.070
| ThreadStore.GetThreadsForUser |  Avg| 192ms| 197ms | 5ms | 2.602
| |  P99| 1.901s| 1.962s | 61ms | 3.208
| ThreadStore.GetTotalThreads |  Avg| 134ms| 133ms | -1ms | -0.746
| |  P99| 1.208s| 1.215s | 7ms | 0.579
| ThreadStore.GetTotalUnreadMentions |  Avg| 132ms| 131ms | -1ms | -0.755
| |  P99| 1.095s| 1.196s | 101ms | 9.223
| ThreadStore.GetTotalUnreadThreads |  Avg| 131ms| 129ms | -2ms | -1.524
| |  P99| 1.036s| 1.08s | 44ms | 4.249
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 132ms| 129ms | -3ms | -2.265
| |  P99| 1.105s| 1.086s | -19ms | -1.719
| ThreadStore.MaintainMembership |  Avg| 17ms| 16ms | -1ms | -5.789
| |  P99| 210ms| 205ms | -5ms | -2.383
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 9ms | -1ms | -10.387
| |  P99| 97ms| 95ms | -2ms | -2.063
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 86ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 93ms | -3ms | -3.112
| TokenStore.Cleanup |  Avg| 3ms| 2ms | -1ms | -30.728
| |  P99| 10ms| 5ms | -5ms | -51.020
| UserAccessTokenStore.GetByToken |  Avg| 106ms| 131ms | 25ms | 23.631
| |  P99| 923ms| 902ms | -21ms | -2.276
| UserStore.AutocompleteUsersInChannel |  Avg| 736ms| 741ms | 5ms | 0.680
| |  P99| 2.98s| 2.701s | -279ms | -9.362
| UserStore.Count |  Avg| 368ms| 324ms | -44ms | -11.956
| |  P99| 972ms| 976ms | 4ms | 0.412
| UserStore.Get |  Avg| 77ms| 72ms | -5ms | -6.479
| |  P99| 885ms| 889ms | 4ms | 0.452
| UserStore.GetAllProfiles |  Avg| 105ms| 104ms | -1ms | -0.956
| |  P99| 981ms| 981ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 1.152s| 1.152s | 0s | 0.000
| |  P99| 2.539s| 2.805s | 266ms | 10.476
| UserStore.GetByUsername |  Avg| 186ms| 170ms | -16ms | -8.607
| |  P99| 2.148s| 976ms | -1.172s | -54.575
| UserStore.GetForLogin |  Avg| 116ms| 112ms | -4ms | -3.435
| |  P99| 951ms| 928ms | -23ms | -2.417
| UserStore.GetMany |  Avg| 192ms| 191ms | -1ms | -0.521
| |  P99| 900ms| 953ms | 53ms | 5.889
| UserStore.GetProfileByIds |  Avg| 104ms| 99ms | -5ms | -4.806
| |  P99| 1.212s| 992ms | -220ms | -18.149
| UserStore.GetProfilesByUsernames |  Avg| 131ms| 131ms | 0s | 0.000
| |  P99| 1.032s| 997ms | -35ms | -3.391
| UserStore.GetProfilesInChannel |  Avg| 86ms| 124ms | 38ms | 44.209
| |  P99| 480ms| 477ms | -3ms | -0.625
| UserStore.GetProfilesNotInChannel |  Avg| 189ms| 339ms | 150ms | 79.208
| |  P99| 977ms| 4.6s | 3.623s | 370.957
| UserStore.GetUnreadCount |  Avg| 144ms| 146ms | 2ms | 1.392
| |  P99| 1.357s| 1.604s | 247ms | 18.205
| UserStore.IsEmpty |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 643ms| 654ms | 11ms | 1.711
| UserStore.Save |  Avg| 84ms| 85ms | 1ms | 1.185
| |  P99| 361ms| 370ms | 9ms | 2.495
| UserStore.Search |  Avg| 393ms| 401ms | 8ms | 2.034
| |  P99| 2.219s| 2.239s | 20ms | 0.901
| UserStore.Update |  Avg| 15ms| 12ms | -3ms | -19.878
| |  P99| 149ms| 97ms | -52ms | -34.958
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 86ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 82ms| 81ms | -1ms | -1.218
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 71ms | 3ms | 4.436
| UserTermsOfServiceStore.GetByUser |  Avg| 152ms| 150ms | -2ms | -1.314
| |  P99| 1.301s| 1.21s | -91ms | -6.996
| WebhookStore.GetOutgoingByTeam |  Avg| 183ms| 182ms | -1ms | -0.548
| |  P99| 1.915s| 1.825s | -90ms | -4.701
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 2.651s| 2.457s | -194ms | -7.319
| | P99| 10s| 10s | 0s | 0.000
| addTeamMember | Avg| 3.76s| 3.767s | 7ms | 0.186
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 588ms| 616ms | 28ms | 4.760
| | P99| 2.476s| 3.744s | 1.268s | 51.214
| autocompleteUsers | Avg| 666ms| 671ms | 5ms | 0.750
| | P99| 2.768s| 2.5s | -268ms | -9.683
| createCategoryForTeamForUser | Avg| 243ms| 430ms | 187ms | 76.873
| | P99| 496ms| 2.425s | 1.929s | 389.042
| createChannel | Avg| 2.265s| 2.201s | -64ms | -2.826
| | P99| 9.25s| 4.933s | -4.317s | -46.669
| createDirectChannel | Avg| 1.343s| 1.243s | -100ms | -7.448
| | P99| 8.542s| 4.664s | -3.878s | -45.401
| createGroupChannel | Avg| 2.494s| 2.996s | 502ms | 20.129
| | P99| 10s| 9.915s | -85ms | -0.850
| createPost | Avg| 3.674s| 3.632s | -42ms | -1.143
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 420ms| 418ms | -2ms | -0.476
| | P99| 2.367s| 2.375s | 8ms | 0.338
| deleteDraft | Avg| 210ms| 208ms | -2ms | -0.953
| | P99| 2.064s| 2.025s | -39ms | -1.890
| deletePost | Avg| 630ms| 699ms | 69ms | 10.961
| | P99| 4.425s| 4.275s | -150ms | -3.390
| followThreadByUser | Avg| 327ms| 326ms | -1ms | -0.306
| | P99| 980ms| 2.23s | 1.25s | 127.501
| getAllTeams | Avg| 141ms| 139ms | -2ms | -1.420
| | P99| 1.166s| 1.001s | -165ms | -14.156
| getCategoriesForTeamForUser | Avg| 319ms| 307ms | -12ms | -3.758
| | P99| 2.422s| 2.382s | -40ms | -1.651
| getChannel | Avg| 531ms| 521ms | -10ms | -1.884
| | P99| 4.713s| 3.131s | -1.582s | -33.570
| getChannelMember | Avg| 181ms| 177ms | -4ms | -2.216
| | P99| 1.929s| 1.938s | 9ms | 0.466
| getChannelMembers | Avg| 100ms| 320ms | 220ms | 220.942
| | P99| 248ms| 980ms | 732ms | 295.459
| getChannelMembersForTeamForUser | Avg| 170ms| 170ms | 0s | 0.000
| | P99| 1.747s| 1.766s | 19ms | 1.088
| getChannelStats | Avg| 123ms| 122ms | -1ms | -0.814
| | P99| 1.962s| 1.965s | 3ms | 0.153
| getChannelUnread | Avg| 175ms| 188ms | 13ms | 7.413
| | P99| 1.721s| 1.87s | 149ms | 8.656
| getChannelsForTeamForUser | Avg| 181ms| 181ms | 0s | 0.000
| | P99| 1.812s| 1.788s | -24ms | -1.325
| getChannelsForUser | Avg| 160ms| 159ms | -1ms | -0.626
| | P99| 1.347s| 1.421s | 74ms | 5.493
| getClientConfig | Avg| 37ms| 35ms | -2ms | -5.345
| | P99| 469ms| 467ms | -2ms | -0.427
| getDrafts | Avg| 215ms| 208ms | -7ms | -3.249
| | P99| 2.154s| 2.082s | -72ms | -3.343
| getFilePreview | Avg| 188ms| 184ms | -4ms | -2.124
| | P99| 1.562s| 1.533s | -29ms | -1.856
| getFileThumbnail | Avg| 187ms| 181ms | -6ms | -3.212
| | P99| 1.688s| 1.636s | -52ms | -3.081
| getPostThread | Avg| 1.02s| 1.022s | 2ms | 0.196
| | P99| 6.497s| 6.463s | -34ms | -0.523
| getPostsForChannel | Avg| 1.791s| 1.966s | 175ms | 9.772
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 599ms| 589ms | -10ms | -1.668
| | P99| 4.591s| 4.551s | -40ms | -0.871
| getPreferences | Avg| 180ms| 188ms | 8ms | 4.433
| | P99| 1.564s| 1.7s | 136ms | 8.698
| getProfileImage | Avg| 92ms| 86ms | -6ms | -6.547
| | P99| 469ms| 471ms | 2ms | 0.426
| getPublicChannelsForTeam | Avg| 219ms| 213ms | -6ms | -2.743
| | P99| 1.996s| 1.93s | -66ms | -3.306
| getTeamMember | Avg| 16ms| 17ms | 1ms | 6.289
| | P99| 247ms| 326ms | 79ms | 31.979
| getTeamMembersForUser | Avg| 115ms| 109ms | -6ms | -5.225
| | P99| 970ms| 937ms | -33ms | -3.401
| getTeamStats | Avg| 544ms| 623ms | 79ms | 14.531
| | P99| 991ms| 2.26s | 1.269s | 128.020
| getTeamsForUser | Avg| 138ms| 141ms | 3ms | 2.181
| | P99| 990ms| 1.211s | 221ms | 22.314
| getTeamsUnreadForUser | Avg| 225ms| 222ms | -3ms | -1.331
| | P99| 2.294s| 2.264s | -30ms | -1.308
| getThreadsForUser | Avg| 202ms| 204ms | 2ms | 0.991
| | P99| 2.1s| 2.121s | 21ms | 1.000
| getUser | Avg| 181ms| 180ms | -1ms | -0.554
| | P99| 1.689s| 1.612s | -77ms | -4.560
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 18ms| 16ms | -2ms | -11.279
| getUsers | Avg| 64ms| 61ms | -3ms | -4.709
| | P99| 871ms| 828ms | -43ms | -4.939
| getUsersByIds | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 367ms| 363ms | -4ms | -1.089
| getUsersByNames | Avg| 133ms| 133ms | 0s | 0.000
| | P99| 1.09s| 1.027s | -63ms | -5.780
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 545ms| 518ms | -27ms | -4.953
| | P99| 4.094s| 3.609s | -485ms | -11.845
| logout | Avg| 341ms| 264ms | -77ms | -22.590
| | P99| 2.11s| 2.005s | -105ms | -4.976
| patchPost | Avg| 1.166s| 1.235s | 69ms | 5.918
| | P99| 8.42s| 10s | 1.58s | 18.765
| removeUserCustomStatus | Avg| 326ms| 280ms | -46ms | -14.117
| | P99| 974ms| 991ms | 17ms | 1.745
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 552ms| 559ms | 7ms | 1.267
| | P99| 3.82s| 4.152s | 332ms | 8.691
| searchAllChannels | Avg| 3.532s| 3.803s | 271ms | 7.673
| | P99| 9.853s| 9.885s | 32ms | 0.325
| searchGroupChannels | Avg| 184ms| 200ms | 16ms | 8.695
| | P99| 1.847s| 2.026s | 179ms | 9.694
| searchPostsInTeam | Avg| 623ms| 587ms | -36ms | -5.776
| | P99| 7.995s| 6s | -1.995s | -24.953
| searchUsers | Avg| 397ms| 405ms | 8ms | 2.013
| | P99| 2.222s| 2.244s | 22ms | 0.990
| setPostReminder | Avg| 972ms| 1.019s | 47ms | 4.838
| | P99| 4.45s| 4.75s | 300ms | 6.742
| unfollowThreadByUser | Avg| 449ms| 480ms | 31ms | 6.906
| | P99| 4.417s| 2.466s | -1.951s | -44.175
| updateCategoriesForTeamForUser | Avg| 1.25s| 1.269s | 19ms | 1.520
| | P99| 7.75s| 4.745s | -3.005s | -38.775
| updatePreferences | Avg| 33ms| 31ms | -2ms | -5.994
| | P99| 323ms| 256ms | -67ms | -20.763
| updateReadStateThreadByUser | Avg| 1.383s| 1.385s | 2ms | 0.145
| | P99| 8.437s| 8.32s | -117ms | -1.387
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -131.137
| | P99| 33ms| 5ms | -28ms | -83.895
| uploadFileStream | Avg| 437ms| 443ms | 6ms | 1.373
| | P99| 1.958s| 1.929s | -29ms | -1.481
| upsertDraft | Avg| 78ms| 78ms | 0s | 0.000
| | P99| 978ms| 989ms | 11ms | 1.124
| viewChannel | Avg| 351ms| 349ms | -2ms | -0.570
| | P99| 2.463s| 2.443s | -20ms | -0.812
